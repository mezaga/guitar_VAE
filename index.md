
# VAE GUITAR

From all the possible notes of an electric guitar processed by ten different effects and different configurations, we employed a Variational Autoencoder to generate audio from the resultant latent space and compare them with a similar analog fx chain. The intention of the present research is to sum up to the outgoing interest to explore the relationships between deep learning models and timbrical variations. The main goal of this research is to propose another perspective of linking analog guitar effects for timbre generation outside the active emulation/recognition studies.

![Guitarra](https://user-images.githubusercontent.com/31640735/170167851-d74f1017-5f94-45d9-8f28-78c10a3f8668.JPG)

## DATASET

We also introduce GUITAR SET a dataset of 8970 real guitar sounds that meticulously explores all the possible notes in a standard tuning electric guitar with different pickup configurations passing through a collection of 12 different analog guitar effects.

### Clean
### Bridge, Middle Bridge, Middle, Middle Neck and Neck
<div class="figure">
    <div align ="left">

        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/versiones_viejas/folder/dataset_examples/Bridge_6-0.wav">
        </audio>
        
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/versiones_viejas/folder/dataset_examples/bridge_Middle_6-0.wav">
        </audio> 
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/versiones_viejas/folder/dataset_examples/middle_6-0.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/versiones_viejas/folder/dataset_examples/Middle_Neck6-0.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/versiones_viejas/folder/dataset_examples/Neck_6-0.wav">
        </audio>
</div>
</div>

### FXs

1. TubeScreamer
2. BluesDriver
3. RAT
4. Chorus
5. Phaser
6. Flanger
7. Tape Echo
8. Sweep Echo
9. Digital Delay
10. Hall Reverb
11. Plate Reverb
12. Spring Reverb


<div class="figure">
    <div align ="left">

        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/versiones_viejas/folder/dataset_examples/TubeScreamer_6-0.wav">
        </audio>
        
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/versiones_viejas/folder/dataset_examples/BluesDriver_6-0.wav">
        </audio> 
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/versiones_viejas/folder/dataset_examples/RAT_6-0.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/versiones_viejas/folder/dataset_examples/Chorus_6-0.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/versiones_viejas/folder/dataset_examples/Phaser_6-0.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/versiones_viejas/folder/dataset_examples/Flanger_6-0.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/versiones_viejas/folder/dataset_examples/Tape_echo6-0.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/versiones_viejas/folder/dataset_examples/SweepEcho_6-0.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/versiones_viejas/folder/dataset_examples/DigitalDlay6-0.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/versiones_viejas/folder/dataset_examples/Hall_Reverb6-0.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/versiones_viejas/folder/dataset_examples/Plate_Reverb6-0.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/versiones_viejas/folder/dataset_examples/Spring_Reverb_6-0.wav">
        </audio>
</div>
</div>

### Reconstruction


Original
![original_reconstruction](https://user-images.githubusercontent.com/92285232/171472384-a29b738b-485f-4d7c-b725-1f305d76410f.png)

Reconstruction
![final_reconstruction](https://user-images.githubusercontent.com/92285232/171472556-42974d6f-94ac-458d-8216-ba6aabb70255.png)

<div class="figure">
    <div align ="left">

        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/final_reconstruction/reconstruction_TubeScreamer.wav">
        </audio>
        
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/final_reconstruction/reconstruction_BluesDriver.wav">
        </audio> 
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/final_reconstruction/reconstruction_RAT.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/final_reconstruction/reconstruction_Chorus.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/final_reconstruction/reconstruction_Phaser.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/final_reconstruction/reconstruction_Flanger.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/final_reconstruction/reconstruction_Tape%20Echo.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/final_reconstruction/reconstruction_Sweep%20Echo.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/final_reconstruction/reconstruction_Digital%20Delay.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/final_reconstruction/reconstruction_Hall%20Reverb.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/final_reconstruction/reconstruction_PlateReverb.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/final_reconstruction/reconstruction_Spring%20Reverb.wav">
        </audio>
</div>
</div>

### Space Interpolations

![clean-BluesDriver](https://user-images.githubusercontent.com/92285232/171486039-09e8293d-fada-455e-a4d3-5c392230b21f.png)

![fft_clean-BluesDriver](https://user-images.githubusercontent.com/92285232/171486067-f59d62ee-fa2d-4101-b46d-6110e0a09334.png)

<div class="figure">
    <div align ="left">

        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_explorationclean-blues/interpolation_CleanBluesDriver0.wav">
        </audio>
        
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_explorationclean-blues/interpolation_CleanBluesDriver1.wav">
        </audio> 
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_explorationclean-blues/interpolation_CleanBluesDriver2.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_explorationclean-blues/interpolation_CleanBluesDriver3.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_explorationclean-blues/interpolation_CleanBluesDriver5.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_explorationclean-blues/interpolation_CleanBluesDriver6.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/Blues-Chorus/interpolation_CleanBluesDriver.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_explorationclean-blues/interpolation_CleanBluesDriver7.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_explorationclean-blues/interpolation_CleanBluesDriver8.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_explorationclean-blues/interpolation_CleanBluesDriver9.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_explorationclean-blues/interpolation_CleanBluesDriver10.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_explorationclean-blues/interpolation_CleanBluesDriver11.wav">
        </audio>
</div>
</div>

![blues-Chorus](https://user-images.githubusercontent.com/92285232/171484534-97d40a55-1fbe-4c4e-9eff-34a7c8d9fc4e.png)

![fft_Blues-Chorus](https://user-images.githubusercontent.com/92285232/171484589-6e415eb8-f21a-4bd4-8dc0-ef8b6fef5556.png)

<div class="figure">
    <div align ="left">

        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/Blues-Chorus/interpolation_BluesDriverChorus0.wav">
        </audio>
        
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/Blues-Chorus/interpolation_BluesDriverChorus1.wav">
        </audio> 
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/Blues-Chorus/interpolation_BluesDriverChorus2.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/Blues-Chorus/interpolation_BluesDriverChorus3.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/Blues-Chorus/interpolation_BluesDriverChorus4.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/Blues-Chorus/interpolation_BluesDriverChorus5.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/Blues-Chorus/interpolation_BluesDriverChorus6.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/Blues-Chorus/interpolation_BluesDriverChorus7.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/Blues-Chorus/interpolation_BluesDriverChorus8.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/Blues-Chorus/interpolation_BluesDriverChorus9.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/Blues-Chorus/interpolation_BluesDriverChorus10.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/Blues-Chorus/interpolation_BluesDriverChorus11.wav">
        </audio>
</div>
</div>


