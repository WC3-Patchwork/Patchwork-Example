# Patchwork Example Map (Lua) (W3X)

This is an example map repository on how patchwork is setup.

## How to use?

- Download & install NodeJS and VSCode
- Clone this repository for your new map.
- Open in VSCode and Run the following premade commands:
  - Install Patchwork
  - Build Map
- In world editor, find and open `build.w3x` map in folder mode, that was generated in this project root.

## Usage notes
After running `Build Map` command you should close the map in the World Editor and re-open it. The editor does not detect these files changes so you have to remind him manually. Additionally, before pressing Test Map, you should manually save the map in the World Editor.

There's also a third command `Explode Map` which will convert map data into text readable formats (script files and JSON files). This is used when you have made some changes to the map using World Editor and you wish to store them in JSON format (with Git).

In case you want to convert an existing map to use Patchwork, you can remove the `map` folder from this project, save your map in folder mode as `build.w3x` (if it's a different filename/extension, you have to change `build.w3x` occurances to the desired name inside `.vscode/launch.json`). Then you can run the `Explode Map` to get your new `map` folder.

In case you have some custom GUI triggers that don't belong to vanilla game or Grapes Extended GUI, you can replace the `.vscode/triggerdata.txt` with the one that your map uses.

## Credits UwU
This example uses [Grape's Extended GUI REV13](https://www.hiveworkshop.com/threads/1-35-grapesofwaths-extended-gui.347569) for GUI trigger conversion.