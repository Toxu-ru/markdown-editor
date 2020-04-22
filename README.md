# markdown-editor
Markdown editor based on pagedown WMD and independent plugin autoIndent.js (attached https://github.com/StackExchange/pagedown)

Further development: https://github.com/femvc/editor

Ready option:

### View

![Внешний вид](https://github.com/Toxu-ru/markdown-editor/blob/master/editor.jpg)

To output:

**Configurable Markdown to HTML converter with Parsedown Extra.**

Configurable Markdown to HTML converter with Parsedown Extra Plugin.

https://github.com/taufik-nurrohman/parsedown-extra-plugin

```
    $Parsedown = new ParsedownExtraPlugin();
    $Parsedown->linkAttributes = array(
        'rel' => 'nofollow' 
    );

    $Parsedown->setMarkupEscaped(true);
    $Parsedown->blockCodeAttributesOnParent = true;
 
    $text = $Parsedown->text($text);
```
