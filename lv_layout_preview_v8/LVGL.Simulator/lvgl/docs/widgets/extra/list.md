```eval_rst
.. include:: /header.rst 
:github_url: |github_link_base|/widgets/list.md
```
# List (lv_list)

## Overview
The List is basically a rectangle with vertical layout to which Buttons and Texts can be added 

## Parts and Styles

**Background**
- `LV_PART_MAIN` The main part of the list that uses all the typical background properties
- `LV_PART_SCROLLBAR` The scrollbar. See the [Base objects](/widgets/obj) documentation for details.

**Buttons and Texts**
See the [/widgets/core/btn](Button)'s and [/widgets/core/label](Label)'s documentation.

## Usage

### Buttons
`lv_list_add_btn(list, icon, text)` adds a full-width button with an icon - that can be an image or symbol - and a text.

The text starts to scroll horizontally if its too long.

### Texts
`lv_list_add_text(list, icon, text)` adds a text.


## Events
No special events are sent by the List, but sent by the Button as usual.

Learn more about [Events](/overview/event).

## Keys
No *Keys* are processed by the object type.

Learn more about [Keys](/overview/indev).

## Example

```eval_rst

.. include:: /lv_examples/src/lv_ex_widgets/lv_ex_list/index.rst

```

## API 

```eval_rst

.. doxygenfile:: lv_list.h
  :project: lvgl
        
```
