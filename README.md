vscode-wgsl-literal
====================

Adds WGSL syntax highlighting for JavaScript template literals.

## Requirements

- Install the [WGSL Extension](https://marketplace.visualstudio.com/items?itemName=PolyMeilex.wgsl)

## Example

```js
const vert = /* wgsl */`
  struct FragmentInput {
    [[location(0)]] Color: vec3<f32>;
  };

  [[stage(fragment)]]
  fn main(input: FragmentInput) -> [[location(0)]] vec4<f32> {
    return vec4<f32>(input.Color, 1.0);
  }
`;

```
