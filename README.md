# alias-dynamo-surface-from-3-or-4-corner-points

Dynamo script for generating surfaces in Autodesk Alias from 3 or 4 corner points.

## Table of Contents
- [Features](#features)
- [Installation / Usage](#installation--usage)
- [Contributing](#contributing)
- [License](#license)



## Features

- **Minimal input requirement** – generates a surface from just 3 or 4 corner points.
- **NURBS surface output** – produces smooth, editable surfaces within Alias.
- **Seamless Alias + Dynamo integration** – designed specifically for this workflow.
- **Simple coordinate input** – add or adjust corner points with ease.
- **Lightweight performance** – efficient execution with minimal overhead.

## Installation / Usage

1. **Download the script**
   - Navigate to the repository.
   - Download the `Surface from 3 or 4 Corner Points.dyn` file.

2. **Open the script in Dynamo Player (within Autodesk Alias)**
   - Launch Autodesk Alias and create 3 or 4 construction points in the scene.
   - Navigate to **Transform → Dynamo Player** to open the Dynamo Player interface.  
     Dynamo Player lets you run scripts without opening Dynamo directly—it loads the inputs and parameters defined in your `.dyn` file automatically.
   - In the Dynamo Player, click the **browse** icon next to **Script Location**, then locate and select the file named:
     ```
     Surface from 3 or 4 Corner Points.dyn
     ```
   - Once the script loads, enter the 3 or 4 corner point coordinates as prompted.
   - Click **Accept** to confirm your selections, then click **Build** to generate the surface based on your inputs.



3. **Run the script**
   - Once loaded, input the 3 or 4 corner point coordinates (if prompted).
   - Use **Dynamo Player** for a smoother execution:
     - Open **Dynamo Player** in Alias.
     - Locate the script in the toolbox or browse to the downloaded `.dyn` file.
     - Configure any exposed input nodes and click **Run**.
    
## Contributing
Contributions welcome! Please open an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.


