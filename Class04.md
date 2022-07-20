# [HOME](README.md)

1. [Class 01](Class01.md)
2. [Class 02](Class02.md)
3. [Class 03](Class03.md)
4. [Class 04](Class04.md)
5. [Class 05](Class05.md)
6. [Class 06](Class06.md)
7. [Class 07](Class07.md)
8. [Class 08](Class08.md)
9. [Class 09](Class09.md)
10. [Class 10](Class10.md)
11. [Class 11](Class11.md)
12. [Class 12](Class12.md)
13. [Class 13](Class13.md)
14. [Class 14](Class14.md)
15. [Class 15](Class15.md)

# CSS Layout

## 1.What is meant by “normal flow”?

Normal flow Normal flow is how the browser lays out HTML pages by default when you do nothing to control page layout. Let's look at a quick HTML example:

I love my cat.

Buy cat food
Exercise
Cheer up friend

The end!

Elements on webpages lay themselves out according to normal flow - until we do something to change that. This article explains the basics of normal flow as a grounding for learning how to change it.

To explain how browsers layout web pages by default before we begin to make changes.

Starting with a solid, well-structured document that's readable in normal flow is the best way to begin any webpage. It ensures that your content is readable even if the user's using a minimal browser or a device such as a screen reader that reads out the page's content. In addition, since normal flow is designed to make a readable document, starting in this way, you're working with the document rather than struggling against it as you make changes to the layout.

## 2. What are a few differences between block-level and inline elements?

Block-level: A Block-level element occupies the entire horizontal space of its parent element (container), and vertical distance equals the height of its contents, thereby creating a "block."

block-level example:

<p>This paragraph is a block-level element; its background has been colored to display the paragraph's parent element.</p>

inline element: Inline elements are those which only occupy the space bounded by the tags defining the element, instead of breaking the flow of the content.

inline example:

<div>The following span is an <span class="highlight">inline element</span>;
its background has been colored to display both the beginning and end of
the inline element's influence.</div>

## 3. ___ positioning is the default for every html element

Static positioning is the default that every element gets. It means "put the element into its normal position in the document flow — nothing special to see here."

Static Positing example:

<p class="positioned"> … </p>

## 4. Name a few advantages to using absolute positioning on an element

This is very useful: we can create isolated UI features that don't interfere with the layout of other elements on the page. For example, popup information boxes, control menus, rollover panels, UI features that can be dragged and dropped anywhere on the page, and so on.

## 5. What is a key difference between fixed positioning and absolute positioning?

This paragraph is a block-level element; its background has been colored to display the paragraph's parent element.

Inline element: Inline elements are those which only occupy the space bounded by the tags defining the element instead of breaking the flow of the content.
