## Algorithms
- [x] A*
- [x] RRT
- [ ] RRT*
- [x] Bidirectional RRT
- [x] Kinodynamic RRT
- [x] Bidirectional Kinodynamic RRT

## Quick Start
1. Install required python packages
    ```bash
    chmod +x install.sh
    ./install.sh
    ```

3. Run the hovercraft demo!
    ```bash
    python demo.py # default to Kinodynamic RRT
    ```
    Choose a different planning algorithm by setting `--algo`, choices are `["RRT", "BiRRT", "KdRRT", "Astar", "BiKdRRT"]`.

