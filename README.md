
# TRANSMIXR Assets Repository

This repository hosts 3D model assets (`.glb` and `.gltf` files) used in the [TRANSMIXR](https://transmixr.eu/) project. The goal is to make these assets publicly accessible and downloadable via direct web links, allowing easy integration in immersive or web-based applications.

## 📁 Folder Structure

All assets are organized in folders by category. For example:

```
TRANSMIXR_Assets/
├── 3D_Models/
│   ├── Earth/
│   │   └── earth_8k_texture.glb
│   ├── Characters/
│   └── Environments/
```

## 🌐 Direct Download Links

Each file in this repository can be accessed directly using the following pattern:

```
https://github.com/Transmixr/TRANSMIXR_Assets/raw/refs/heads/main/<folder>/<subfolder>/<filename>.glb
```

### Example

To download the Earth model with 8K textures:

[earth_8k_texture.glb](https://github.com/Transmixr/TRANSMIXR_Assets/raw/refs/heads/main/3D_Models/Earth/earth_8k_texture.glb)

## 🔧 How to Use ? Integration with Spatial Media Server

You can use the download link with the OSC command:

```
/SpatialMedia/Model/Path [string]
```

This instructs the Spatial Media server to load a 3D asset in the application.

### Example Integrations

- **Cuez Automator**:  
  Use the `3D` block and paste the download link into the **Link** label.

- **OpenStageControl**:  
  In the **3D Models** module, use the **Path** input field to enter the link.

Make sure the path points to a valid `.glb` or `.gltf` asset from this repository using the format:

```
https://github.com/Transmixr/TRANSMIXR_Assets/raw/refs/heads/main/<folder>/<subfolder>/<filename>.glb
```

```

## 📜 License

Unless otherwise specified, all assets are shared for use within the scope of the TRANSMIXR project. Please refer to individual folders for licensing information where applicable.

---

For more information about the TRANSMIXR project, visit [transmixr.eu](https://transmixr.eu/).

