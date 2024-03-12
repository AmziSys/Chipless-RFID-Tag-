# Chipless-RFID-Tag

------------------- Chipless radio frequency identification (Chipless RFID) Tag -------------------


* The idea is to design a chipless RFID tag that enables data encoding of 10-bits (meaning 1024 different code words are possible) in a 3.52-4.54 GHz band.

* Design:
    - The tag is based on multiple G-shaped resonators and generates multiple resonances by modifying the length of each resonator.
    - Each G resonator of a different length introduces a different stop band resonance.
    - The presence of resonance at a particular frequency is used to encode a logic ‘1’ and the absence of resonance is used to encode a logic ‘0’.
    - With "n" resonators only "2xEn" combinations are possible.

*Results:
  - the simulated magnitude of the proposed circuit, consisting of 10 resonators shows the operating frequencies: 3.52 GHz, 3.65 GHz, 3.76 GHz, 3.87 GHz, 4.02 GHz, 4.11 GHz, 4.25 GHz, 4.34 GHz, 4.43 GHz and 4.54 GHz. This result proves the chosen design to encode the bits "1111111111".
    
* The Tage was designed using CST-MWS.
