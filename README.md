# Pocket-LoC
<img align = "right" src="https://user-images.githubusercontent.com/42568983/202521498-0bb95a05-1dd4-4db9-ad12-fc51b9aba1ed.jpg" width="40%" /> 
Lab-on-chip (LoC) technology is becoming increasingly relevant, especially in the field of medicine. However, often LoC setups rely on complex lab equipment for operation. The aim of this project is to create an affordable and portable LoC setup as a proof-of-concept for truly pocket-sized LoC - the Pocket LoC.

Pocket LoC can be assembled with standard equipment found in a typcial engineering lab (such as a maker space or FabLab). Once assembled, Pocket LoC is fully portable and only needs a PC to operate.

## Microfluidic Chip
This repository contains instructions and templates for making your own microfluidic chip. Principally, Pocket LoC can work with any transparent chip that fits the sensor dimensions. However, we would like to provide some guidance on how to get started.

### Materials
The microfluidic chips described here consist of PDMS (i.e. silicone) on a glass substrate. The necessary moulds are 3D-printed.

You will need the following components and tools:
- 3D-printer
- printing filament (we achieved best results with ABS or PETG, e.g. [black PETG](https://www.prusa3d.com/product/prusament-petg-jet-black-1kg/))
- silicone elastomer (many materials may work, we use [Sylgard 184](https://www.dow.com/en-us/pdp.sylgard-184-silicone-elastomer-kit.01064291z.html#overview))
- microscope slides as substrate
- vacuum desiccator and vacuum pump (or a lab with vacuum supply)
- fine scales for mixing the silicone
- heat plate (optional)

### Chip Design
The design of your microfluidic chip will depend on your individual application. If you just want to try the Pocket LoC with a simple droplet experiment we suggest using a large channel width of 1mm, that does not require any specific precision when manufacturing the chip. A sample mould is provided in the CAD folder.

Inlets can be designed as a press-fit for the [tubing]((https://darwin-microfluidics.com/collections/silicone-tygon-tubing/products/mp-t-1-3-mm-tygon-tubing-for-bartels-micropumps)) used for the Pocket LoC. Outlets can al
