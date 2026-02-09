## Explore the Logical Hierarchy
- Open the hierarchy browser by clicking on the button shown from the top bar or by selecting the menu View -> Hierarchy Browser
- The block window looks like as shown below
- The Hierarchy Browser lists cell (instance) names of sub-design modules (M) and hard macros (HM) along with their statistics
- Expand the width of the hierarchy tab to see the columns displaying the statistics, or double-click on the title bar (to the right of Hierarchy ) to maximize the view
- The following statistics are displayed, Utilization percentage; pin count; hard marcos, standard cell, and net count (at the current level only hierarchically)
- Click on the "+" sign to the left of the I_SDRAM_TOP module to expand its hierarchy
- Select one of the hard macros (HM). Notice that the selected hard marco is highlighted with a white "X" in the layout view. We can select and highlight multiple hard marcos by using the [Ctrl] or [Shift] keys
- Unselect the hard marco(s) by clicking the cursor in any black area around the layout or pressing the hotkey [Ctrl-D]
- Right-click on any module(M), and from the context menu select Color by Hierarchy -> Initialize Color by Hierarchy
- The hierarchies/modules were highlighted in the layout using a different color as shown below
Note: Fusion Compiler will draw Hierarchical module boundaries (MB) around the various modules in the design
- Smaller modules are not highlighted in the GUI to reduce clutter, for example, the module I_PARSER remains as M, and if we select I_PARSER nothing is highlighted in the layout view
- Right-click on the I_PARSER module, and from the context menu select Color by Hierarchy -> Create Selected. The I_PARSER module is now shown as MB, and the corresponding standard cells can be seen in new color in the layout view
- To disable all coloring right-click a module then select Color by Hierarchy -> Remove All
