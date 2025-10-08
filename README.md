# Online gscn calculator
● gscn_calculator: https://dustinchen26.github.io/gscn_calculator

● ssb_advance: https://dustinchen26.github.io/ssb_calculator_advance/

## (1) freq to arfcn calculator
ex:
Input freq(Hz): 3603840 => Output arfcn = 640256

## (2) arfcn to freq calculator
ex:
Input arfcn: 640256 => Output Freq = 3603840 Hz

## (3) gscn calculator
```
Please input
ex:(band, carrierBw(RB), freq_low, freq_high)=(78, 273, 3603840, 3603840) / (79, 273, 4849860, 4849860) / (41, 273, 2565750, 2565750)
band: 78
carrierBw(RB): 273
freq_low: 3603840
freq_high: 3603840

Calculate
gscn=7890, absFreqPointA=3554700, absArfcnPointA=636980, absFreqSsb=3563040, absArfcnSsb=637536, dlEarfcn=640256, nDlCenterFreq=3603840, Kssb=4, offsetToPointA=26
                 <dlBwpCfg>
                    <mu>KHz30</mu>
                    <numRb>273</numRb>
                 </dlBwpCfg>
                 <dlFreqInfo>
                    <absFreqPointA>3554700</absFreqPointA>
                    <absArfcnPointA>636980</absArfcnPointA>
                    <absFreqSsb>3563040</absFreqSsb>
                    <absArfcnSsb>637536</absArfcnSsb>
                    <nrFreqBand>78</nrFreqBand>
                    <subCarrierCfg>
                       <offsetToCarrier>0</offsetToCarrier>
                       <subCarrierSpacing>KHz30</subCarrierSpacing>
                       <carrierBw>273</carrierBw>
                    </subCarrierCfg>
                    <bSChannelBwDL>100MHZ</bSChannelBwDL>
                    <dlEarfcn>640256</dlEarfcn>
                 </dlFreqInfo>  
                 <ulBwpCfg>
                    <mu>KHz30</mu>
                    <numRb>273</numRb>
                 </ulBwpCfg>
                 <ulFreqInfo>
                    <absFreqPointA>3554700</absFreqPointA>
                    <absArfcnPointA>636980</absArfcnPointA>
                    <nrFreqBand>78</nrFreqBand>
                    <subCarrierCfg>
                       <offsetToCarrier>0</offsetToCarrier>
                       <subCarrierSpacing>KHz30</subCarrierSpacing>
                       <carrierBw>273</carrierBw>
                    </subCarrierCfg>
                    <bSChannelBwUl>100MHZ</bSChannelBwUl>
                    <ulEarfcn>640256</ulEarfcn>
                 </ulFreqInfo>
                 <nDlCenterFreq>3603840</nDlCenterFreq>
                 <nUlCenterFreq>3603840</nUlCenterFreq>
                 <nDlBw>100</nDlBw>
                 <nUlBw>100</nUlBw>
```
