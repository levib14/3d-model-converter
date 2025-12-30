# 3D File Format Converter

A simple browser-based tool to convert between different 3D file formats. No installation required, all processing happens locally in your browser.

## Features

- Convert between multiple 3D file formats
- Drag and drop file upload
- 100% client-side - your files never leave your device
- No signup or installation needed
- Modern, responsive interface

## Supported Formats

**Input Formats**: OBJ, STL, PLY, GLTF, GLB, 3MF, FBX, DAE  
**Output Formats**: OBJ, STL, PLY, GLTF, GLB

### Format Details

- **OBJ** - Wavefront Object (widely compatible)
- **STL** - Stereolithography (3D printing standard)
- **PLY** - Polygon File Format (supports vertex colors)
- **GLTF** - GL Transmission Format (web-optimized, preserves materials)
- **GLB** - Binary GLTF (single-file, compact)
- **3MF** - 3D Manufacturing Format (modern 3D printing format, input only)
- **FBX** - Filmbox (game engines, animation)
- **DAE** - Collada (open standard for 3D assets)

## How to Use

1. Upload your 3D file (click or drag and drop)
2. Select the output format you want
3. Click "Convert & Download"
4. Your converted file will download automatically

## Notes

- 3MF files can be imported but not exported (Three.js limitation)
- For 3D printing, STL output is recommended as the most universal format
- Large files (>50MB) may cause performance issues
- Materials and textures are best preserved when converting GLTF ↔ GLB

## License

MIT
