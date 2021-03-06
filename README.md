

## csstosvg

Dependency free(!) way to easily apply CSS box-shadow rules to SVG elements. Optionally you can use it with libraries such as D3, jQuery and Zepto.

Example CSS strings you can pass to csstosvg:

box-shadow: 3px 3px teal;

box-shadow: 4px 5px 4px black;

box-shadow: 2px 2px 2px 1px rgba(0, 0, 0, 0.2);

box-shadow: inset 5px 1px gold;


## Usage

csstosvg.apply( obj,'box-shadow: 4px 4px 2px red;');

'obj' must be one of:
- SVG DOM element
- D3 object
- jQuery / Zepto object

## Gist

Live Example [csstosvg Gist](https://gist.github.com/sunsetrainbow/90ecf7fd1174191f01b4)

## Limitations
- You can't specify multiple shadows on the same object (yet).
- You may use pixels or percentages for sizes but not 'em' or other units.
- Behavior will differ from pure CSS when the border of the OBJECT element is larger than a few pixels.
