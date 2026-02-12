# Stacker

Stratigraphic forward model for simulating migration of patches in shallow-water carbonates 

### Installation and running instructions

**Prerequisites:**
- MATLAB (tested with versions 2018+)

**Installation:**
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/Stacker.git
   cd Stacker
   ```

**Running the model:**
1. Open MATLAB and navigate to the `src/` directory
2. Run the model by typing:
   ```matlab
   stacker
   ```
3. The GUI will open. Use the interface to:
   - Load a parameter file (default: `parameters/stackerFaciesMosaic.txt`)
   - Initialize the model
   - Run the simulation
   - Plot results

**Available parameter configurations:**
- `stackerFaciesMosaic.txt` - Facies mosaic model configuration
- `stackerFaciesBelt.txt` - Facies belt model configuration

### Repository structure
```
Stacker/
├── src/                           # Source code and model files
│   ├── stacker.m                  # Main Stacker model script
│   ├── parameters/                # Input parameter files
│   │   ├── faciesMosaicCloud*.mat # Facies mosaic cloud configurations (1-5)
│   │   ├── initialTopographyShallowRampSmoothedNoise.txt  # Initial topography data
│   │   ├── sealevelCurveConstant0m.txt                    # Sea level curve data
│   │   ├── stackerFaciesBelt.txt                          # Facies belt configuration
│   │   └── stackerFaciesMosaic.txt                        # Facies mosaic configuration
│   └── modelResults/              # Output directory for model results
│       └── FaciesMosaic.mat       # Example output file
├── docs/                          # Documentation
│   └── index.html                 # Documentation homepage
├── CITATION.cff                   # Citation information
├── CONTRIBUTING.md                # Contribution guidelines
├── LICENSE                        # Apache 2.0 License
└── README.md                      # This file
```

## Authors

__Peter Burgess__  
University of Liverpool  
Web page: [www.liverpool.ac.uk/environmental-sciences/staff/peter-burgess](https://www.liverpool.ac.uk/environmental-sciences/staff/peter-burgess/)  
ORCID: [0000-0002-3812-4231](https://orcid.org/0000-0002-3812-4231)

### Public repository maintenance:

__Emilia Jarochowska__  
Utrecht University  
email: e.b.jarochowska [at] uu.nl  
Web page: [www.uu.nl/staff/EBJarochowska](https://www.uu.nl/staff/EBJarochowska)  
ORCID: [0000-0001-8937-9405](https://orcid.org/0000-0001-8937-9405)

__Xianyi Liu__  
Utrecht University  
email: x.liu6 [at] uu.nl  
Web page: [www.uu.nl/staff/XLiu6](https://www.uu.nl/staff/XLiu6)  
ORCID: [0000-0002-3851-116X](https://orcid.org/0000-0002-3851-116X)

## Manual 

The manual pages https://mindthegap-erc.github.io/Stacker/ have been generated based on the code using an LLM and reviewed by the author and the maintainers. The latter take responsibility for the contents.

## Copyright

Copyright 2024-2026 University of Liverpool

## License

Apache 2.0 License, see LICENSE file for license text.
