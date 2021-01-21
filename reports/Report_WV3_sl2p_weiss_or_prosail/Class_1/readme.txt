Output of SL2P matlab calibration code (github/rfernand/sl2p/code) run using Parameter file WV3_sl2p_weiss_or_prosail.xls..

Details

WV3 - applies to WV3 Surface Reflectance (Level 2) products scaled to 0-1 using bands most similar to Sentienl 2 MSI version of SL2P
input band list
      Green, 510 - 580 nm,  0-1
      Red, 630 - 690 nm,  0-1
      Red edge, 705 - 745 nm,  0-1
      Near-IR1, 770 - 895 nm,  0-1
      Near-IR2, 860 - 1040 nm, 0-1
      SWIR-3, 1640 - 1680 nm
      SWIR-6, 2185 - 2225 nm
      cos(SZA),  0-1
      cos(VZA),  0-1
      cos(RAA),  0-1
sl2p - uses SL2P neural network inversion algorithm
weiss - uses calibraton database pdfs as defined in Weiss and Baret, 2016
or - uses orthongonal sampling of database as in Weiss and Baret, 2016
prosail - uses prosail radiative transfer algorithm to simulate database
