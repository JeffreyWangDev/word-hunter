# Word-Hunter
A XY gantry system to play the GamePigeon game Word Hunt. Project for Hack Club Undercity!

<img width="844" height="634" alt="image" src="https://github.com/user-attachments/assets/873782df-94c3-4f82-9829-089fa519c28a" />

Cad file: https://cad.onshape.com/documents/58a2db96d60cbe98c4c1362c/w/5696988daa510935751d6292/e/5618d55c88ffba036bcec4c8?renderMode=0&uiState=6889818a7952d605cf46fb6e

A Camera module takes a picture of the board. It then uploads the image to OpenAI's 4o model to read and process the letters on the screen. The Python script then uses a dictionary file to generate the best words and their swipe paths, which is sent to the XY gantry system with two stepper motors holding an Apple Pencil to play the game.

# Bill of Materials

| Item                          | Quantity | Link |
|-------------------------------|----------|------|
| 2mm Pitch GT2 Belt (9mm Thick) | 1 | [Amazon](https://www.amazon.com/Seekliny-Non-Slip-Creality-Anycubic-Artillery/dp/B0CX1CXZH2?source=ps-sl-shoppingads-lpcontext&ref_=fplfs&psc=1&smid=A2DGLVBBDAJTOF&gQT=2) |
| NEMA 17 Stepper Motor        | 2 | [StepperOnline](https://www.omc-stepperonline.com/fr/nema-17-bipolaire-59ncm-84oz-in-2a-42x48mm-4-fils-avec-1m-de-cable-et-connecteur-17hs19-2004s1) |
| V Wheels                     | 9 | [Amazon](https://www.amazon.com/V-Slot-Aluminum-Profiles-Printer-Special/dp/B0F4PNHJXP?gQT=1) |
| Short Aluminum Extrusion    | 5 | [Amazon](https://www.amazon.com/European-Standard-Anodized-Aluminum-Extrusion/dp/B09JSN97Y9?source=ps-sl-shoppingads-lpcontext&ref_=fplfs&psc=1&smid=A2E52U58FCDBRC&gPromoCode=14155643339598177024&gQT=1) |
| Long Aluminum Extrusion     | 1 | [Amazon](https://www.amazon.com/European-Standard-Anodized-Aluminum-Extrusion/dp/B09JSN97Y9?source=ps-sl-shoppingads-lpcontext&ref_=fplfs&psc=1&smid=A2E52U58FCDBRC&gPromoCode=14155643339598177024&gQT=1) |
| Breadboard                  | 1 | [Pololu](https://www.pololu.com/product/4000?gQT=1) |
| Stepper Motor Driver A4988  | 3 | [Pololu](https://www.pololu.com/product/1182) |
| High-Torque Servo Motor     | 1 | [Adafruit](https://www.adafruit.com/product/1142?gQT=1) |
| Screws and Nuts             | – | – |
| Raspberry Pi 5              | 1 | [Amazon](https://www.amazon.com/Raspberry-Pi-8GB-SC1112-Quad-core/dp/B0CK2FCG1K?source=ps-sl-shoppingads-lpcontext&ref_=fplfs&psc=1&smid=A3FPRP7I8FTOOJ) |
| Web Camera                  | 1 | [Amazon](https://www.amazon.com/FWV-Streaming-Microphone-Desktop-Studying/dp/B0D72VQR6Q?source=ps-sl-shoppingads-lpcontext&ref_=fplfs&psc=1&smid=A36LVV2HAP7FK3&gQT=1) |
| Perfboard                   | 1 | [DigiKey](https://www.digikey.com/en/products/detail/schmalztech,-llc/ST-PERF-1-3/15786862?gQT=1) |



Note: This algorithm and detection code were written by @Eddy Zhou at https://github.com/eddyzow/Word-Hunter/. This is just a updated repo for all files.  
