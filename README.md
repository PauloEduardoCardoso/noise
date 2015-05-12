# noise
Obtain Lden Noise Indicator based on Ld, Le, Ld by applying the formula:
10 * log10((1/24)*((13  * (10^( ld.r / 10))) + (3 * (10^((len.r + 5) / 10))) + (8 * (10^((ln.r + 10) / 10)))))

The function will import *topologically corrected* shapefiles originally produced by [windPRO DECIBEL module](http://www.emd.dk/windpro/windpro-modules/environment-modules/decibel/) and produce the Lden noise indicator in raster.

Additional info from [apambiente](http://www.apambiente.pt/_zdata/DAR/Ruido/NotasTecnicas_EstudosReferencia/GuiaPraticoMedicoesRuidoAmbiente.pdf)
