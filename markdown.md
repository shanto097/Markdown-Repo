# Hypertext Markup Language (HTML)

## Intro to HTML
Basic structure of a webpage is marked with HTML. HTML consists of tags, attributes and contents. Tags denote what is and how to be shown in a page where attributes denote additional properties about tags. Contents are actual things that are shown in a page. HTML document has two main tags - `HEAD` and `BODY`. Meta information such as external document (script, stylesheet) link, webpage title etc. are shown in `HEAD`. The `BODY` part contains the actual contents to be shown in a webpage.

Basic structure of a webpage are shown bellow:
```html
<!DOCTYPE html>
<html>
  <head>
    meta info about the webpage resides here
  </head>
  <body>
    actual contents of a webpage resides here
  </body>
</html>
```

## Tags/Elements
HTML elements are classified into two major types.
- Container Tag - Has both opening & ending tag
  - Heading
  - Paragraph
  - Table
- Empty Tag - Only has opening tag, no ending tag
  - Line-Break
  - Image
  - Link, etc.

### Example of a Container Tag - `<table>...</table>`
In the example bellow `<table>` tag is a container tag. It has both starting tag and ending tag. other elements are nested Inside this tag. Which in terms nest other elements. Container tag contains contents inside the starting and ending tag.

**Code Snippet**

```HTML
<table>
  <tr>
    <th>Name</th>
    <th>Institution</th>
  </tr>
  <tr>
    <td>Hafizul Haque</td>
    <td>CSE, CUET</td>
  </tr>
  <tr>
    <td>Mahmudur Rahman</td>
    <td>EEE, BUET</td>
  </tr>
</table>
```
**Output**

| Name | Institution |
| --- | --- |
| Hafizul Haque | CSE, CUET  |
| Mahmudur Rahman | EEE, BUET |

### Example of an Empty tag - `<img>`
In the example bellow `<img>` tag is a empty tag as it doesn't have any ending tag. It doesn't nest any other elements. Note here we defined different properties of the img using attributes- some of them are mandatory (e.g. src) whereas some are optional. General syntax of a tag using a attribute is: `<tag attr_name="attr_value">..contents..</tag>`. Content and ending tag portions are omitted in case of empty tag.

**Code Snippet**

```HTML
<img
  src="parrot.jpg"
  alt="picture of a parrot"
  width="300px"
  height="200px"
/>
```

**Output**

<img src="parrot.jpg" alt="picture of a parrot" width="300px" height="200px" style="display: block; margin: 0 auto;">


For full tag list follow this [`link`](https://w3school.org/tag_list).

## HTML Demo
A simple webpage marked using HTML is shown bellow:

![A simple blog webpage](webpage.PNG)


## Conclusion
> *We had just gotten the internet; it was so slow, but I would view the  source code, copying and pasting the HTML , trying to figure out how it all worked. I had no Idea, but I wanted to teach myself.*
>
> -**I. Justine**

The best way to learn something is to do experimenting with it, explore it with curiosity. So have passion, seek with curiosity. There's tons of learning materials and curious and eager people to help you on your way.
