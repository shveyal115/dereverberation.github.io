# Magnitude or Phase? a Two Stage Algorithm for  Single-Microphone Dereverberation

Ayal Schwartz, Sharom Gannot and Shlomo E. Chazan 

Int.Workshop on Acoustic Signal Enhancement (IWAENC), 2024

![flow](/flow5.png)

In this work, we present a new single-microphone speech dereverberation algorithm. Initially, we provide empirical evidence highlighting the importance of separate processing for magnitude and phase in dereverberation tasks. Additionally, we illustrate that in our task, unlike noise reduction, certain objective metrics strongly correlate with the magnitude while others with the phase. Consequently, we propose a new architecture that consists of two modules, each of which is responsible for a different task. The first module estimates the clean magnitude, while the second is focused on estimating the phase using the noisy input phase with the estimated magnitude. Subjective tests indicate that enhancing either only the magnitude or only the phase components is insufficient for this task. In our experimental evaluation, the proposed method demonstrates a consistent improvement in the magnitude and phase compared to prior approaches that primarily address one of these aspects.

## Table of Examples

| Noisy | RI2RI | MM+Noisy phase | MM+PM (our) |
|-------|-------|-------|-------|
| ![Noisy 1](path/to/noisy1.png) | ![RI2RI 1](path/to/ri2ri1.png) | ![MM+NP 1](path/to/mmnp1.png) | ![MM+PM 1](path/to/mmpm1.png) |
| ![Noisy 2](path/to/noisy2.wav) | ![RI2RI 2](path/to/ri2ri2.wav) | ![MM+NP 2](path/to/mmnp2.wav) | ![MM+PM 2](path/to/mmpm2.wav) |
| ![Noisy 3](path/to/noisy3.wav) | ![RI2RI 3](path/to/ri2ri3.wav) | ![MM+NP 3](path/to/mmnp3.wav) | ![MM+PM 3](path/to/mmpm3.wav) |
| ![Noisy 4](path/to/noisy4.wav) | ![RI2RI 4](path/to/ri2ri4.wav) | ![MM+NP 4](path/to/mmnp4.wav) | ![MM+PM 4](path/to/mmpm4.wav) |
| ![Noisy 5](path/to/noisy5.wav) | ![RI2RI 5](path/to/ri2ri5.wav) | ![MM+NP 5](path/to/mmnp5.wav) | ![MM+PM 5](path/to/mmpm5.wav) |
| ![Noisy 6](path/to/noisy6.wav) | ![RI2RI 6](path/to/ri2ri6.wav) | ![MM+NP 6](path/to/mmnp6.wav) | ![MM+PM 6](path/to/mmpm6.wav) |
| ![Noisy 7](path/to/noisy7.wav) | ![RI2RI 7](path/to/ri2ri7.wav) | ![MM+NP 7](path/to/mmnp7.wav) | ![MM+PM 7](path/to/mmpm7.wav) |
| ![Noisy 8](path/to/noisy8.wav) | ![RI2RI 8](path/to/ri2ri8.wav) | ![MM+NP 8](path/to/mmnp8.wav) | ![MM+PM 8](path/to/mmpm8.wav) |
| ![Noisy 9](path/to/noisy9.wav) | ![RI2RI 9](path/to/ri2ri9.wav) | ![MM+NP 9](path/to/mmnp9.wav) | ![MM+PM 9](path/to/mmpm9.wav) |
| ![Noisy 10](path/to/noisy10.wav) | ![RI2RI 10](path/to/ri2ri10.wav) | ![MM+NP 10](path/to/mmnp10.wav) | ![MM+PM 10](path/to/mmpm10.wav) |


