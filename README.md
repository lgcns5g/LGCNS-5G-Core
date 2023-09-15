<p align="center"><a href="https://github.com/lgcns5g/LGCNS-5G-Core" target="_blank" rel="noopener noreferrer"><img width="700" src="https://github.com/lgcns5g/LGCNS-5G-Core/blob/main/assets/img/LG%20CNS%205G%20Core.png" alt="LG CNS 5G Core logo"></a></p> 

LG CNS 5G Core is a solution based on the 3GPP specifications for the 5G Core Network.  
This repository is only for Control Plane of the 5G Core Network. For User Plane, visit [here](https://github.com/lgcns5g/LGCNS-5G-Core-UPF).  
Control Plane is based on [Open5GS](https://github.com/open5gs/open5gs).

We only provide patches for the Control Plane in accordance with the GNU Affero General Public License.

### Control Plane
- Access and Mobility Management Function (AMF)
- Authentication Server Management Function (AUSF)
- Network Repository Function (NRF)
- Session Management Function (SMF)
- Unified Data Management (UDM)
- Unified Data Repository (UDR)
- Network Slicing Selection Function (NSSF)
- Policy and Charging Function(PCF)
- Binding Support Function(BSF)

## Getting Started
Please apply the patches before building.  
 1. Clone the original source files of Open5GS
     - You can find the Open5GS tag that is compatible with the patch files in the Release Notes
 2. Apply the patch file provided in this repository
 3. Build and Deploy

#### 1. Source-based building and deployment
The building and deployment process is the same as the one mentioned in [documentation of Open5GS](https://open5gs.org/open5gs/docs/guide/02-building-open5gs-from-sources/).

#### 2. Container-based building and deployment
You can build using the [Dockerfile of Open5GS](https://github.com/open5gs/open5gs/tree/main/docker) and deploy to Kubernetes using the container image.

## Community 
- Problem with LG CNS 5G Core can be filed as [issues](https://github.com/lgcns5g/LGCNS-5G-Core/issues) in this repository.
- Other topics related to this project are happening on the [discussions](https://github.com/lgcns5g/LGCNS-5G-Core/discussions).
- Email are available for inquiries at support5g@lgcns.com.

## Contributing  
Anyone can contribute to the codebase by submitting a pull request.  
Contributions can be simple bugfixes, advices and remarks on the design, architecture, coding/implementation.

## Release Notes
Please refer to the [Release Notes](https://github.com/lgcns5g/LGCNS-5G-Core/releases).

## License 
Control Plane is distributed under the GNU Affero General Public License.([GNU AGPL v3.0](https://github.com/lgcns5g/LGCNS-5G-Core/blob/main/LICENSE))  
