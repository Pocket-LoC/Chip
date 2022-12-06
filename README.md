# Pocket LoC
<img align = "right" src="https://user-images.githubusercontent.com/42568983/202521498-0bb95a05-1dd4-4db9-ad12-fc51b9aba1ed.jpg" width="40%" /> 
Lab-on-chip (LoC) technology is becoming increasingly relevant, especially in the field of medicine. However, often LoC setups rely on complex lab equipment for operation. The aim of this project is to create an affordable and portable LoC setup as a proof-of-concept for truly pocket-sized LoC - the Pocket LoC.

Pocket LoC can be assembled with standard equipment found in a typical engineering lab (such as a maker space or FabLab). Once assembled, Pocket LoC is fully portable and only needs a PC to operate.

## Microfluidic Chip
<img align = "right" src="https://user-images.githubusercontent.com/42568983/205295270-1c095b07-2bd6-400f-94e1-f13bbbd8ab20.jpg" width="40%" />

This repository contains instructions and templates for making your own microfluidic chip. Principally, Pocket LoC can work with any transparent chip that fits the sensor dimensions. However, we would like to provide some guidance on how to get started.

### Materials
The microfluidic chips described here consist of PDMS (i.e. silicone) on a glass substrate. The necessary moulds are 3D-printed.

You will need the following components and tools:
- 3D-printer
- printing filament (we achieved best results with ABS or PETG, e.g. [black PETG](https://www.prusa3d.com/product/prusament-petg-jet-black-1kg/))
- silicone elastomer (many materials may work, we use [Sylgard 184](https://www.dow.com/en-us/pdp.sylgard-184-silicone-elastomer-kit.01064291z.html#overview))
- microscope slides as substrate
- vacuum chamber and pump (or a lab with vacuum supply)
- fine scales for mixing the silicone
- heat plate (optional)

### Design
The design of your microfluidic chip will depend on your individual application. If you just want to try the Pocket LoC with a simple droplet experiment we suggest using a large channel width of 1mm, that does not require any specific precision when manufacturing the chip. Have a look at the sampple mould.

Inlets can be designed as a press-fit for the [tubing]((https://darwin-microfluidics.com/collections/silicone-tygon-tubing/products/mp-t-1-3-mm-tygon-tubing-for-bartels-micropumps)) used for the Pocket LoC. The same applies for outlets.

Your channel structure should have a straight section, paralell to the chips long side, with a length of at least 6mm to use the Pocket LoC sensor. You may also have to print custom position holders (see the [housing repository](https://github.com/Pocket-LoC/Housing/tree/main/CAD) for some samples) to fit your channel structure.

### Manufacture
These instructons refer to Sylgard 184 elastomer. If you are using different silicone, start with the mixing and curing parameters suggested by the manufacturer and adjust the mix ration and curing time depending on your results.

1. Design and print your chip mould and a rake (used in step 6). Usually it is a good idea to make a few chips at once, as some may fail. Samples for both the rake and the chip are provided - you may have to adjust the size of the teeth of the rake depening on your printer and channel structure.
      <p float="left">
        <img src="https://github.com/Pocket-LoC/Chip/blob/main/Photos/00%20printed%20parts.jpg" width="22%" />
      </p>
2. Pour together the two components of the silicone kit using fine scales to get a ratio of 1:10. Typically, about 15g of mixture is a sufficient amount for one microfluidic chip. Mix the components well using a spoon or spatula for at least two minutes.
      <p float="left">
        <img src="https://github.com/Pocket-LoC/Chip/blob/main/Photos/01%20elastomer%20kit.jpg" width="22%" />
        <img src="https://github.com/Pocket-LoC/Chip/blob/main/Photos/02%20mix.jpg" width="22%" />
        <img src="https://github.com/Pocket-LoC/Chip/blob/main/Photos/03%20stirred.jpg" width="22%" />
      </p>

3. Place the silicone mixture in the vacuum chamber and evacuate the air to remove bubbles from the mixture. Wait for at least two minutes before ventilating the chamber again. Repeat approx. 10-20 times until all visible bubbles have been removed.
      <p float="left">
        <img src="https://github.com/Pocket-LoC/Chip/blob/main/Photos/04%20chamber.jpg" width="22%" align='center' />
        <img src="https://github.com/Pocket-LoC/Chip/blob/main/Photos/05%20chamber%20vacuum.jpg" width="22%" align='center' />
        <img src="https://github.com/Pocket-LoC/Chip/blob/main/Photos/06%20chamber%20air.jpg" width="22%" align='center' />
        <img src="https://github.com/Pocket-LoC/Chip/blob/main/Photos/07%20degassed.jpg" width="22%" align='center' />
      </p>

4. Pour the degassed silicone mixture into the mould, filling it to the brim. Then place it on a heat plate or in a lab oven to cure at 100°C for 60 minutes.
      <p float="left">
        <img src="https://github.com/Pocket-LoC/Chip/blob/main/Photos/08%20poured.jpg" width="22%" />
      </p>

5. Carefully pull the chip structure out of the mould. Start by lifting it at the edge with a thin screwdriver. You will see a fine grid caused by the 3D-print on the bottom of the chip. Remove any unwanted silicone residue. Depending on your chip structure and size it may be easier to break apart the mould.
      <p float="left">
        <img src="https://github.com/Pocket-LoC/Chip/blob/main/Photos/09%20remove.jpg" width="22%" />
        <img src="https://github.com/Pocket-LoC/Chip/blob/main/Photos/10%20cured%20top.jpg" width="22%" />
      </p>

6. Use the rake to spread a thin and consistent layer of silicone on a clean microscope slide. Then carefully place the cured silicone chip on top and press lightly. You can use the grid structure as a visual aid: Ideally, it should only just not be visible any more. Adjust the size of the rake if the layer is too thin (chip will not attach properly) or too thick (your chip will be clogged once cured).
      <p float="left">
        <img src="https://github.com/Pocket-LoC/Chip/blob/main/Photos/20%20components%20glass.jpg" width="22%" />
        <img src="https://github.com/Pocket-LoC/Chip/blob/main/Photos/21%20layer%20spread.jpg" width="22%" />
        <img src="https://github.com/Pocket-LoC/Chip/blob/main/Photos/22%20complete.jpg" width="22%" />
      </p>

7. Cure the chip for another 60 minutes at 100°C.

8. Your microfluidic chip is now ready to go. You may find some fine tuning of the manufacturing procedure for your needs and tools may improve the chip performance (e.g. reproducibility of droplet generation or pressure tolerance).
