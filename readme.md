# React Native Flexbox Sample

- Flexbox provides consistent layout on different screen sizes.
- Use a combination of `flexDirection`, `alignItems`, and `justifyContent` to create a layout.
- `flex` defines how your items are going to “fill” over the available space along the main axis. 
- Space will be divided according to each element's flex property.

## Flex Direction
- `flexDirection` controls the direction in which the children of a node are laid out.
    
    ### Column    
    - `column` is the **default value**.  
    - Aligns children from top to bottom.

    ### Row
    - `row` aligns children left to right.

    ### Column Reverse
    - `column-reverse` aligns children from top to bottom.

    ### Row Reverse
    - `row-reverse` aligns children left to right.


## Justify Content
- `justifyContent` describes how to align children within the main axis of their container.
    
    ### Flex Start
    - `flex-start` is the **default value**.
    - Aligns children of a container to the start of the containers main axis.

    ### Flex End
    - `flex-end` aligns children of a container to the end of the container's main axis.

    ### Center
    - `center` aligns children of a container to the center of the container's main axis.

    ### Space Between
    - `space-between` evenly spaces children across the container's main axis, distributing the remaining space **between** the children.

    ### Space Around
    - `space-around` evenly spaces off children across the container's main axis, distributing the remaining space **around** the children.

    ### Space Evenly
    - `space-evenly` evenly distributes children within the alignment container along the main axis.


## Align Items
- `alignItems` describes how to align children along the cross axis of their container.  Similar to `justifyContent`.

    ### Stretch
    - `stretch` is the **default value**.
    - Stretches the children of a container to match the `height` of the container's cross axis.

    ### Flex Start
    - `flex-start` aligns children of a container to the end of the container's cross axis.

    ### Flex End
    - `flex-end` aligns children of a container to the end of the container's cross axis.

    ### Center
    - `center` aligns children of a container in the center of the container's cross axis.

    ### Baseline
    - `baseline` aligns children of a container along a common baseline.


## Align Self
- `alignSelf` has the same options and effect as `alignItems` but instead of affecting the children within a container, you can apply this property to a single child to change its alignment within its parent.


## Flex Wrap
- The 'flexWrap' property is set on containers and it controls what happens when children overflow the size of the container along the main axis. 


## Align Content
- `alignContent` defines the distribution of lines along the cross-axis.  
- Only has effect when items are wrapped to multiple lines using `flexWrap`.

    ### Flex Start
    - `flex-start` is the **default value**.
    - Aligns wrapped lines to the start of the container's cross axis.

    ### Flex End
    - `flex-end` aligns wrapped lines to the end of the container's cross axis.

    ### Stretch
    - `stretch` stretches wrapped lines to match the height of the container's cross axis. **default value when using Yoga on the web**

    ### Center
    - `center` aligns wrapped lines in the center of the container's cross axis.

    ### Space Between
    - `space-between` evenly spaces wrapped lines across the container's cross axis, distributing the remaining space **between** the lines.

    ### Space Around
    - `space-around` evenly spaces wrapped lines across the container's cross axis, distributing the remaining space **around** the lines.


- More info can be found in the [React Native docs](https://reactnative.dev/docs/flexbox). 