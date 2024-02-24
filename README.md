# Blueprint Grid
![BPG Cover](http://www.blueprintgrid.com/core/files/images/bpg-social.jpg)

Blueprint Grid is a multi-method CSS and javascript library for creating responsive or dynamic layouts for mobile apps and websites. It is free and open source under the MIT license.

Blueprint Grid is the layout component for [Brutalist Framework](https://www.brutalistframework.com). 

Built with:
* Flexbox CSS
* CSS grid
* Vanilla javascript

There are five methods for creating layouts: 
1. **B3Grid**: Blocks and Bricks Base Grid (Flexbox-based)
2. **CSS grid**: auto-adjusting layouts based on CSS grid
3. **Print Grid**: paper-friendly print grid
4. **Bento Grid**: dynamic auto-fill layout grid
5. **Chaos Grid**: anti-grid grid with (optional) random positioning
6. **PolyGrids**: experimental grids with multiple dimensions

## Getting Started
You will need: 
* **/source/blueprintgrid.css**
* **/source/methods/js/bento-grid.js** (if using Bento Grid method)
* **/source/methods/js/chaos-grid.js** (if using Chaos Grid method)

The **blueprintgrid.css** file will import all the grid method CSS files from the **/source/methods** directory, which contains the following method CSS source files:
* **b3grid.css**
* **bento-grid.css**
* **bootstrap-grid.css**
* **chaos-grid.css**
* **css-grid.css**
* **media-queries.css**
* **polygrids.css**
* **print-grid.css**
* **variables.css**

The above files can be referenced independently. The CSS variables file is imported into each of the other files, EXCEPT FOR media-queries and bootstrap-grid.

### Documentation
You can find detailed documentation in the [Blueprint Grid Wiki](https://github.com/pinecreativelabs/Blueprint-Grid/wiki).

### DEMOS
You can see live demos at: [BlueprintGrid.com](https://www.blueprintgrid.com).
