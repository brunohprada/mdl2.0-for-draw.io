# Documentation

## IMPORTANT WARNINGS

- This is an beta version.
- Official documentation is available in https://mdlmodel.com/.

## About MDL 2.0 - Micro Development Language

### What has changed from version 1.0 to 2.0?

The way to represent layers: Now we can use the Part to represent the layers (Tiers and Layers), in addition to being able to be used to compose any element. This allows for greater ease and flexibility.

The way to represent the frontend:

![Frontend representation](https://mdlmodel.com/public/images/components/frontend.svg)

The change was made not to confuse Part and Frontend, being chosen a common component in practically all diagram editors, so that the change will not generate any burden.

Connectors: Connectors have been kept, but can now be used on ALL elements, including Parts. There is also a greater incentive to use more text in connectors so that they are better "interpretable". Less need for "turn" connectors, as long as the understanding of the drawing is clear.

Possibility of use of images and icons for component design.

Using "[" and "]" between conditions and logical expressions that is, how the link between 2 elements occurs.

All in a single view: Purpose of enabling an evolutionary design. Diagrams can be born functional and be evolved, continued to be more comprehensive and cover the structure. All elements can use a "#"+ text or "<<"+text+">>" to indicate what the element is. For example: a system, a data instance, a table, a technology, etc.

## About this project

This project aims to provide elements based on the MDL 2.0 Model to be used in the draw.io diagramming software.

## How to use the elements

1. Download the latest release of this project.
2. Open [draw.io](https://app.diagrams.net/) in your browser or the app installed on your desktop.
3. With the app open, click File, and then click Open Library
4. Go to the folder where you saved the release and select the file `MDL Library.xml` and you are done!
