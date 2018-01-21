# SeedStick
ATTINY85 IOTA SEED Management

DIY Build of IOTA SEED Management consists of the components:
- USB-Case as a 3D Print
- ATTINY85 Digispark USB Board
- (Optional Photoresistor)
- Arduino Development Environment with ATTINY85 drivers (http://arduiono.cc)
- 2 Versions of Code
- 1. Plug & Play needs only the board, add the one Seed in the code and compile (Community edition)
- 2. Nine (9) Seed Version needs some small assembly of a Photoresistor and some work, provided by a Youtube video (tbd>)

Plug and Play Version
---------------------
Overview:
1. Assembly
- Place the Board into the USB-Case (3D-Print).
- Doubleclick on the INO-File and open it.
- place your SEED into the 1st line of code (new SEED can be created here)
- compile code
- upload the code to the USB Board and add the Board to the USB Connector

2. Useage
- Open your IOTA Wallet
- place the cursor to the SEED entry
- add the SeedStick
- SeedStick fills in the SEED
- Remove the SeedStick (dont't forget)
- Only at 1st Useage: write the 3 letter shortcode (Wallet output) of the SEED onto this new build SeedStick case 
  (to identify which Stick is the right one if there are several)
  
3. Problems
- if you add the SeedStick the SEED will be placed anywhere where the cursor is located
- Be always sure that your cursor is where the SEED should be inserted.

4. Safety
- Add the SeedStick to insert the SEED, remove the SeedStick immediately
- Keep complete Github repository and Arduino INO - Files on a USB-Stick and execute:
- 1. download and run Arduino from a USB Stick 
- 2. then close your network 
- 3. add SEED to code 
- 4. compile and upload code to SeedStick
- 5. remove SeedStick and close, remove the Arduino environment incl. USB Stick
- 6. connect, open to your network
- 7. open IOTA Wallet, place cursor to the SEED entry
- 8. test and use it: stick the SeedStick to a USB port and wait 1-2 seconds to fill in
- 9. remove SeedStick
- Be happy 

5. Handling the Arduino environment
- <tbd>
