# Synapse:Connect | Synapse:Runtime | Neuron

A professional node-based animation authoring system for game development and animation production.

## Access Required

<div align="center">

[![Become a Patron](https://img.shields.io/badge/Patreon-F96854?style=for-the-badge&logo=patreon&logoColor=white)](https://www.patreon.com/c/filmstorm/membership)

**[🎮 Join our Patreon](https://www.patreon.com/c/filmstorm/membership)** - Access Synapse tier required

*App authentication is handled through Patreon OAuth - your membership is verified automatically*

</div>

## Overview

Synapse:Connect is a visual programming environment for creating complex animation networks. Build animation graphs using nodes, connect them to create behaviors, and export to game engines.

## Core Modules

### Synapse:Connect
The main application providing a node graph editor for animation authoring:
- **Visual Node Editor** - Intuitive drag-and-drop interface for building animation networks
- **FBX Import** - Load animations, skeletons, and meshes from FBX files
- **Real-time Preview** - See your animation network in action as you build
- **Parameter System** - Control animations with float and vector2 parameters

### Synapse:Runtime (Development Starting Soon)
The runtime animation system that will execute your animation graphs:
- **Efficient Playback** - Optimized animation blending and evaluation (planned)
- **Network Compilation** - Convert node graphs to runtime-ready format (planned)
- **Cross-platform** - Designed for integration with game engines (planned)
- **Status**: Development to begin after core Connect features are stable

### Neuron (Early Development)
Dynamic motion synthesis for procedural animation:
- **Physics-based Animation** - Real-time motion generation
- **COM Balance** (Work in Progress) - Center of mass balancing system
- **Stagger System** (Work in Progress) - Dynamic reactions to impacts
- **Self-preservation** (Work in Progress) - Procedural protective reactions

## Visual Showcase

<div align="center">

### 🎬 Features in Action

#### Footstep Synchronization
![Footstep Sync Demo](https://your-domain.com/gifs/footstep-sync.gif)
*Blend2Node automatically synchronizes foot contacts between animations*

#### Time Synchronization
![Time Sync Demo](https://your-domain.com/gifs/time-sync.gif)
*Perfect timing alignment across different animation speeds*

#### Root Motion & Trajectory Visualization
![Root Trajectory](https://your-domain.com/gifs/root-trajectory.gif)
*See past and future motion paths rendered in viewport*

#### Timeline Recording & Analysis
![Timeline Recording](https://your-domain.com/gifs/timeline-recording.gif)
*Evaluate node graph and scrub through recorded results for precise debugging*

#### Neuron Physics (Early Preview)
![Neuron Balance](https://your-domain.com/gifs/neuron-balance.gif)
*Dynamic balance recovery system in development*

![Neuron Stagger](https://your-domain.com/gifs/neuron-stagger.gif)
*Procedural stagger reactions to impacts*

</div>

## Key Features

### Animation Nodes
- **Blend Node** - Mix two animations with weight control
- **Blend2 Node** - Advanced blending with foot sync and time sync options
- **Motion Matching** (Work in Progress) - Database-driven animation selection
- **State Machine** (To be implemented) - Logic-based animation transitions
- **IK Nodes** - Two-bone IK, FABRIK, and aim constraints
- **Additive Blend** - Layer animations on top of base motion

### Specialized Tools
- **Footstep Editor** - Mark and edit foot contact timing
- **Root Motion Extraction** - Extract movement for constant timeline playback, ensuring consistent motion regardless of animation speed
- **Root Trajectory Rendering** - Visualize past and future root motion paths in 3D viewport
- **Timeline Recording** - Evaluate the node graph, then scrub through the recorded timeline to analyze exactly what's happening frame by frame
- **Timeline Editor** - Scrub through animations and edit timing
- **Property Panel** - Fine-tune node parameters

## System Requirements

### Minimum
- **OS**: Ubuntu 20.04+ or compatible Linux distribution
- **CPU**: Dual-core 2.0 GHz
- **RAM**: 4 GB
- **GPU**: OpenGL 3.3 compatible
- **Storage**: 500 MB available space
- **Dependencies**: Qt6 libraries

### Recommended
- **OS**: Ubuntu 22.04+
- **CPU**: Quad-core 3.0 GHz
- **RAM**: 8 GB
- **GPU**: Dedicated graphics with OpenGL 4.5
- **Storage**: 2 GB available space

## Installation

### Windows
**Coming Soon!** Windows release is in development and will be available shortly.

### Linux

1. Download the latest release:
   ```bash
   wget https://github.com/filmstorm/synapse-connect-releases/releases/latest/download/SynapseConnect-0.1.0-linux-x86_64.tar.gz
   ```

2. Extract the archive:
   ```bash
   tar xzf SynapseConnect-0.1.0-linux-x86_64.tar.gz
   ```

3. Navigate to the directory:
   ```bash
   cd SynapseConnect-0.1.0-linux-x86_64
   ```

4. Run the application:
   ```bash
   ./run.sh
   ```

### Dependencies

If you encounter missing library errors, install Qt6:
```bash
sudo apt install qt6-base-dev libqt6widgets6 libqt6opengl6-dev libqt6network6
```

## Getting Started

1. **Launch** - Run `./run.sh` to start Synapse:Connect
2. **Authenticate** - Sign in with your Patreon account (Access Synapse tier required)
3. **Create Project** - File → New Project
4. **Import Animation** - File → Import FBX
5. **Build Network** - Drag nodes from catalog, connect them
6. **Preview** - Hit play to see your animation network in action
7. **Analyze** - Stop playback and scrub the timeline to examine recorded frames

### Authentication

The app uses Patreon OAuth for authentication. On first launch:
- Click "Authenticate with Patreon"
- Log in to your Patreon account
- Authorize Synapse:Connect
- The app verifies your Access Synapse tier membership
- Authentication is cached locally for convenience

## Current Status

- **Stable**: Core node editor, FBX import, basic blending
- **Beta**: Motion matching, footstep editor
- **Alpha**: Neuron physics system
- **Planned**: Synapse:Runtime, State machine transitions, advanced IK

## Updates

The application includes an auto-updater. Check for updates via Help → Check for Updates.

## Support

Report issues on the GitHub repository. This software requires Access Synapse tier to support ongoing development.

## Get Access

<div align="center">
<a href="https://www.patreon.com/c/filmstorm/membership">
<img src="https://img.shields.io/badge/Become_a_Patron-Support_Development-F96854?style=for-the-badge&logo=patreon&logoColor=white" alt="Support on Patreon" />
</a>

**Access Synapse Tier** required:

• Full access to Synapse:Connect  
• Support development and testing  
• Help shape the future of the project  
• Access to all updates

</div>

## License

Proprietary software. Access Synapse tier on Patreon required to use the application.

---

<div align="center">

**Synapse:Connect** - Professional Animation Authoring for Games

[![Patreon](https://img.shields.io/badge/Patreon-Join_Now-F96854?style=flat-square&logo=patreon&logoColor=white)](https://www.patreon.com/c/filmstorm/membership) [![Platform](https://img.shields.io/badge/Platform-Linux-blue?style=flat-square)](https://github.com/filmstorm/synapse-connect-releases) [![Windows](https://img.shields.io/badge/Windows-Coming_Soon-orange?style=flat-square)](https://github.com/filmstorm/synapse-connect-releases)

</div>
