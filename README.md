# HQ NextPCB Active Manufacturing
### Get PCB quotations within KiCad and order with a single click

HQ NextPCB's Active manufacturing plugin will help you:
- Extract key manufacturing parameters from your design
- Get real-time quotations from NextPCB within KiCad
- Generate Gerber files and upload them to NextPCB along with your personal board settings

Once the upload is complete, you can use the HQDFM Gerber Viewer to double check your manufacturing files, adjust board parameters then add it to your NextPCB cart directly.
![NextPCB Plugin](https://github.com/HubertHQH/HQ-NextPCB/assets/125419974/b7002006-7fc4-4a02-be14-cd5ab3bb0774)

## Features
### Automatic parameter extraction
When launching the plugin, the following parameters will be extracted from your KiCad design:
- Layer count
- Board size (x,y)
- Board thickness
- Minimum trace width/spacing
- Minimum drill hole size
  
*Note: These parameters cannot be edited from the plugin as they are extracted directly from your KiCad design.*

### Real-time quotations completely within KiCad
Click the "Update Price" button to get the latest pricing and lead time for your boards from NextPCB.

You can modify other parameters (E.g. solder mask color, board quantity, etc.) at any time and re-quote the price with a click of a button. All the options are synced with [NextPCB](https://www.nextpcb.com/).

*Note: Some combinations are restricted (E.g. white silkscreen cannot be chosen with white solder mask).*

### One-click Gerber generation and sync to the [HQ NextPCB PCB order page](https://www.nextpcb.com/pcb-quote)
Click the "Place Order" button to generate Gerber and NC drill files and upload them straight to NextPCB's order page along with your board parameters.

Everything is in sync, so no additional adjustments are required. Of course, you are free to change the settings on the website and then proceed to order.

## Installation
Open the "Plugin and Content Manager" from the main window. Click "Manage" and add the plugin repository: https://raw.githubusercontent.com/HQNEXTPCB/HQNEXTPCB-kicad-addone-repository/main/repository.json
![image](https://github.com/HubertHQH/HQ-NextPCB/assets/125419974/9eab30a3-de23-4e1d-900d-e9d89ad397f1)
Switch to the repository, install and apply pending changes:
![image](https://github.com/HubertHQH/HQ-NextPCB/assets/125419974/4910fef3-e984-4fa4-a889-37dae5d5e300)

### About HQ NextPCB
HQ NextPCB specializes in reliable multilayer PCB manufacture and assembly, and like KiCad, our goal is to enable engineers to build tomorrow's electronics. NextPCB is working with KiCad to provide smart tools to simplify the progression from design to physical product. With 3 major factories catering to prototyping, mass production and PCB assembly, and over 15 years of engineering expertise, NextPCB believes our industrial experience will prove invaluable to KiCad users and the PCB design community.

We are a [KiCad Platinum Sponsor](https://www.nextpcb.com/blog/kicad-nextpcb-platinum-sponsorship).
