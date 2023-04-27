---
title: "Brief Reviews of Science Advances: Volume 9, Issue 16 (April 21, 2023)"
excerpt: "Brief Review on 'Resistless EUV lithography: Photon-induced oxide patterning on silicon' "


header:
  overlay_image: /assets/images/Science_Advances_Journal.png
  overlay_filter: rgba(4, 56, 115, 0.7)


categories:
  - Brief Review
tags:
  - [EUV Lithography]

toc: true
toc_sticky: true
 
date: 2023-04-27
last_modified_at: 2023-04-27
---

This review is written by **non-expert** and used for **personal** study only.
{: .notice--danger}

## Resistless EUV lithography: Photon-induced oxide patterning on silicon
- **<U>EUV Lithography</U>**

The paper examines the **challenges of photolithography** in semiconductor manufacturing, particularly the limitations imposed by light wavelength. The authors explore the potential of **extreme ultraviolet (EUV) lithography** as a solution to overcome these restrictions and enable further miniaturization of semiconductor devices. However, conventional photoresists suffer from resolution and line-edge roughness limitations due to their stochastic nature. To address this issue, the authors investigate the use of **partially hydrogen-terminated silicon (H-terminated Si) for resistless EUV lithography**.

The researchers demonstrate the use of the **achromatic Talbot lithography technique** for high-resolution patterning on hydrofluoric acid (HF)-treated Si surfaces. Upon exposure to EUV light, a dense oxide layer forms, which is subsequently transferred to the Si substrate through etching. X-ray photoelectron spectroscopy (XPS) results reveal a different mechanism from scanning tunneling microscopy (STM)-based lithography, as silicon oxides form under EUV exposure. The authors believe that this approach may **overcome resolution limitations** of traditional photoresists and enable the **upscaling of devices for quantum computing applications**.

The paper describes a **resistless lithography process** that patterns Si using EUV exposure on partially H-terminated Si surfaces. The process starts with a p-type Si(100) wafer immersed in a buffered HF solution to remove its native oxide layer. The wafer is then loaded into an EUV interference lithography vacuum chamber, selectively exposed to EUV light, and etched in tetramethylammonium hydroxide (TMAH) solution to transfer the oxide pattern to the Si substrate. The researchers optimize the process by experimenting with various exposure and etching parameters, ultimately finding that adding isopropyl alcohol (IPA) to the TMAH solution enhances sensitivity and anisotropic etching behavior.

The researchers explore the mechanism of the resistless lithography process by conducting exposures at two photon energies, below and above the Si absorption edge. They discover that Si etch depth saturates almost at the same point for both energies and attribute the higher rate of oxide formation to the increased availability of secondary electrons due to increased absorption and photoelectron yield. To make this work relevant for industrial integration, the authors propose tuning the photon energy to $91.9$ eV, corresponding to a wavelength of $13.5$ nm, and perform further experiments at this energy and wavelength.

Using **synchrotron radiation-based XPS**, the researchers investigate the oxidation process at the exposed Si surface and the effect of EUV photons on the HF-treated Si(100) surface. They compare survey scans of various Si surfaces and find that the oxygen signal is significantly lower in HF-treated Si compared to untreated Si, indicating successful removal of native oxide and passivation. Additionally, they observe an increase in the oxygen signal with increasing EUV doses, pointing to an oxide formation mechanism.

The authors successfully demonstrate **nanoscale patterning on HF-treated Si surfaces without a photoresist** by using EUV exposure and TMAH etching. They find that EUV exposure leads to the formation of a stable oxide layer in the exposed areas, with increased SiO$_x$ formation at higher EUV doses. This results in higher etch resistance in the TMAH solution. They also demonstrate dense line/space patterns with a $75$-nm half-pitch using EUV attenuated total reflection lithography and TMAH etching, although the obtained nanopattern exhibits relatively high roughness.

While the demonstrated patterning mechanism requires higher doses than state-of-the-art EUV resists and is not suitable for high-volume manufacturing, it serves as a **proof of concept for resistless patterning using EUV light**. The authors expect further research to focus on developing inorganic materials and surface monolayers with increased EUV absorption and faster solubility switch. The integration of this technique with **selective area doping** or **atomic layer deposition (ALD)** could enable wafer-scale patterning of interconnects in quantum devices.

In summary, the paper presents a promising approach to overcome the limitations of photolithography in semiconductor manufacturing by using **resistless EUV lithography on partially H-terminated Si surfaces**. The researchers successfully demonstrate high-resolution patterning with the achromatic Talbot lithography technique and show that EUV exposure promotes the formation of a stable oxide layer in exposed areas. Although the method currently requires higher doses than conventional EUV resists, it serves as a proof of concept for resistless patterning with EUV light and has the potential to enable high-resolution patterning for quantum computing devices and future semiconductor manufacturing nodes.

Future research is expected to focus on improving the efficiency of the process by developing materials with increased EUV absorption and faster solubility switches. Additionally, the combination of this technique with selective area doping or ALD could lead to innovative wafer-scale patterning solutions for interconnects in quantum devices. As the field continues to evolve, these advancements have the potential to revolutionize semiconductor manufacturing and contribute to the development of next-generation quantum devices.



>**Required Additional Study Materials**
> 
> - M. A. Walsh, M. C. Hersam, Atomic-scale templates patterned by ultrahigh vacuum scanning tunneling microscopy on silicon. Annu. Rev. Phys. Chem. 60, 193–216 (2009).
> - Y. K. Ryu, R. Garcia, Advanced oxidation scanning probe lithography. Nanotechnology 28, 142003 (2017).
> <details>
> <summary>Introductory material</summary>
> <div markdown="1">
> - **“EUV Lithography”** edited by Vivek Bakshi
> </div>
> </details>

**<U>Reference</U>**

SCIENCE ADVANCES 19 Apr 2023 Vol 9, Issue 16 DOI: 10.1126/sciadv.adf5997