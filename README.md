# FNO_Localization
Microseismic source localization using Fourier Neural Operator with application to field data from Utah FORGE

Seismologists recognize the localization of earthquakes as a primary and complex task. Determining the seismic event’s location is essential for analyzing seismic activity. The event’s location is inverted from seismic waves recorded by receivers at the surface or in a borehole. Although numerous methods have been developed to solve this problem, they face computational and physics limitations. This study introduces a data-driven approach utilizing Fourier Neural Operators (FNOs) for real-time microseismic event localization. The proposed method aims to construct a resolution-invariant model that can be rapidly evaluated with a single forward pass, eliminating the need for retraining. Initially, a 2D FNO model is trained to solve the eikonal equation and tested on both simple and complex velocity models such as the Marmousi model. The method achieves high accuracy in identifying event locations, even for complex settings. Finally, the proposed approach is applied to field data from Utah FORGE, demonstrating its potential for industrial applications. By applying FNO to the actual microseismic dataset obtained from the operational well within the EGS setting, the research showcases the model’s capability to accurately determine hypocenter locations. Through this study, we validate the effectiveness of FNO in source localization under realistic conditions, accounting for challenges such as partial data coverage. Our approach paves the way for real-time microseismic monitoring, as the trained FNO model can be promptly evaluated to determine the source location, facilitating real-time decisionmaking to ensure the safe and efficient development of subsurface operations.

![Method](https://github.com/ayratabd/FNO_Localization/blob/master/FNO.png)

## Libraries
The scripts work with Pytorch 2.1.1.


## Citation
If you find our work useful in your research, please cite:
```
@article{abdullin2024fnoloc,
  title={Microseismic source localization using Fourier Neural Operator with application to field data from Utah FORGE},
  author={Abdullin, Ayrat and bin Waheed, Umair and Suleymanli, Kanan and Stanek, Frantisek},
  journal={IEEE Transactions on Geoscience and Remote Sensing},
  pages={},
  year={2024},
  publisher={Elsevier}
}
```

## Contact
If you have any questions, please feel free to email the author.
