vscode-wgsl-literal
====================

Adds WGSL syntax highlighting for JavaScript template literals.

## Example

```js
const vert = /* wgsl */`
  attribute vec4 aVertexPosition;
  uniform mat4 uModelViewMatrix;
  uniform mat4 uProjectionMatrix;
  void main() {
    gl_Position = uProjectionMatrix * uModelViewMatrix * aVertexPosition;
  }
`;

```