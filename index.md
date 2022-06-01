
# VAE GUITAR

From all the possible notes of an electric guitar processed by twelve different effects and different configurations, we employed a Variational Autoencoder to generate audio from the resultant latent space and compare them with a similar analog fx chain. The intention of the present research is to sum up to the outgoing interest to explore the relationships between deep learning models and timbrical variations. The main goal of this research is to propose another perspective of linking analog guitar effects for timbre generation outside the active emulation/recognition studies.

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

Clean - Blues Driver

![clean-BluesDriver](https://user-images.githubusercontent.com/92285232/171486039-09e8293d-fada-455e-a4d3-5c392230b21f.png)

![fft_clean-BluesDriver](https://user-images.githubusercontent.com/92285232/171486067-f59d62ee-fa2d-4101-b46d-6110e0a09334.png)

<div class="figure">
    <div align ="left">

        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/clean-blues/interpolation_CleanBluesDriver0.wav">
        </audio>
        
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/clean-blues/interpolation_CleanBluesDriver1.wav">
        </audio> 
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/clean-blues/interpolation_CleanBluesDriver2.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/clean-blues/interpolation_CleanBluesDriver3.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/clean-blues/interpolation_CleanBluesDriver5.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/clean-blues/interpolation_CleanBluesDriver6.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/clean-blues/interpolation_CleanBluesDriver.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/clean-blues/interpolation_CleanBluesDriver7.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/clean-blues/interpolation_CleanBluesDriver8.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/clean-blues/interpolation_CleanBluesDriver9.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/clean-blues/interpolation_CleanBluesDriver10.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/clean-blues/interpolation_CleanBluesDriver11.wav">
        </audio>
</div>
</div>

Blues Driver - Flanger

![BluesDriver-Flanger](https://user-images.githubusercontent.com/92285232/171486631-c7d4f354-3ed8-40cd-9ed8-9541b05fafe3.png)

![fft_Blues-Flanger](https://user-images.githubusercontent.com/92285232/171486676-5fb7ed1d-961c-4a23-830a-e7c3eec43e34.png)

<div class="figure">
    <div align ="left">

        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/Blues-Flanger/interpolation_BluesDriverFlanger0.wav">
        </audio>
        
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/Blues-Flanger/interpolation_BluesDriverFlanger1.wav">
        </audio> 
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/Blues-Flanger/interpolation_BluesDriverFlanger2.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/Blues-Flanger/interpolation_BluesDriverFlanger3.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/Blues-Flanger/interpolation_BluesDriverFlanger4.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/Blues-Flanger/interpolation_BluesDriverFlanger5.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/Blues-Flanger/interpolation_BluesDriverFlanger6.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/Blues-Flanger/interpolation_BluesDriverFlanger7.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/Blues-Flanger/interpolation_BluesDriverFlanger8.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/Blues-Flanger/interpolation_BluesDriverFlanger9.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/Blues-Flanger/interpolation_BluesDriverFlanger10.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/Blues-Flanger/interpolation_BluesDriverFlanger11.wav">
        </audio>
</div>
</div>

Flanger - Sweep Echo

![Flanger-SweepEcho](https://user-images.githubusercontent.com/92285232/171487691-59ce39f6-f763-45ac-9869-c073d95b4da3.png)

![fft_Flanger-SweepEcho](https://user-images.githubusercontent.com/92285232/171487757-431ff09a-159c-409f-b572-fd22196cb90f.png)

<div class="figure">
    <div align ="left">

        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/Flanger-SweepEcho/interpolation_FlangerSweep%20Echo0.wav">
        </audio>
   
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/Flanger-SweepEcho/interpolation_FlangerSweep%20Echo1.wav">
        </audio> 
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/Flanger-SweepEcho/interpolation_FlangerSweep%20Echo2.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/Flanger-SweepEcho/interpolation_FlangerSweep%20Echo3.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/Flanger-SweepEcho/interpolation_FlangerSweep%20Echo4.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/Flanger-SweepEcho/interpolation_FlangerSweep%20Echo5.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/Flanger-SweepEcho/interpolation_FlangerSweep%20Echo6.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/Flanger-SweepEcho/interpolation_FlangerSweep%20Echo7.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/Flanger-SweepEcho/interpolation_FlangerSweep%20Echo8.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/Flanger-SweepEcho/interpolation_FlangerSweep%20Echo9.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/Flanger-SweepEcho/interpolation_FlangerSweep%20Echo10.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/Flanger-SweepEcho/interpolation_FlangerSweep%20Echo11.wav">
        </audio>
</div>
</div>

Sweep Echo - Hall Reverb

![SweepEcho-Hall](https://user-images.githubusercontent.com/92285232/171488477-d150a551-3fd4-4606-ba72-e9c12a58df82.png)

![fft_SweeEcho-Hall](https://user-images.githubusercontent.com/92285232/171488508-3b07d9bd-6cdb-4ff1-a101-4ed57fbc3927.png)

<div class="figure">
    <div align ="left">

        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/SweepEcho-HallReverb/interpolation_Sweep%20EchoHall%20Reverb0.wav">
        </audio>
        
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/SweepEcho-HallReverb/interpolation_Sweep%20EchoHall%20Reverb1.wav">
        </audio> 
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/SweepEcho-HallReverb/interpolation_Sweep%20EchoHall%20Reverb2.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/SweepEcho-HallReverb/interpolation_Sweep%20EchoHall%20Reverb3.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/SweepEcho-HallReverb/interpolation_Sweep%20EchoHall%20Reverb4.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/SweepEcho-HallReverb/interpolation_Sweep%20EchoHall%20Reverb5.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/SweepEcho-HallReverb/interpolation_Sweep%20EchoHall%20Reverb6.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/SweepEcho-HallReverb/interpolation_Sweep%20EchoHall%20Reverb7.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/SweepEcho-HallReverb/interpolation_Sweep%20EchoHall%20Reverb8.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/SweepEcho-HallReverb/interpolation_Sweep%20EchoHall%20Reverb9.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/SweepEcho-HallReverb/interpolation_Sweep%20EchoHall%20Reverb10.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/bb14bdcd95eb1260a320e5ba2ebb8cd2722e7eb2/space_exploration/SweepEcho-HallReverb/interpolation_Sweep%20EchoHall%20Reverb11.wav">
        </audio>
</div>
</div>

Real Fx

![spectrograms](https://user-images.githubusercontent.com/92285232/171489174-d659aff4-c8bc-4c72-a4db-c4ef10234bed.png)

![waveforms](https://user-images.githubusercontent.com/92285232/171489203-45bc968f-5a94-4576-9fe7-10f238bc37c4.png)

<div class="figure">
    <div align ="left">

        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/analog_fx/0-CL-6-0.wav">
        </audio>
        
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/analog_fx/0-CL-6-12.wav">
        </audio> 
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/analog_fx/1-CL-BD-6-0.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/analog_fx/1-CL-BD-6-12.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/analog_fx/2-BD-FL-6-0.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/analog_fx/2-BD-FL-6-12.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/analog_fx/3-FL-DL-6-0.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/analog_fx/3-FL-DL-6-12.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/analog_fx/4-DL-RV-6-0.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/analog_fx/4-DL-RV-6-12.wav">
        </audio>
</div>
</div>

One Octave Interpolation

![8va_interpolation](https://user-images.githubusercontent.com/92285232/171490694-e69fd34c-eda3-43f7-8854-25cf7248367f.png)

![fft_8va_interpolation](https://user-images.githubusercontent.com/92285232/171490726-5e691dfa-c4ee-48b4-822e-153ccf9f3591.png)

<div class="figure">
    <div align ="left">

        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/space_exploration/8va%20interpolation/interpolation_8va_E2_E30.wav">
        </audio>
        
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/space_exploration/8va%20interpolation/interpolation_8va_E2_E31.wav">
        </audio> 
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/space_exploration/8va%20interpolation/interpolation_8va_E2_E32.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/space_exploration/8va%20interpolation/interpolation_8va_E2_E33.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/space_exploration/8va%20interpolation/interpolation_8va_E2_E34.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/space_exploration/8va%20interpolation/interpolation_8va_E2_E35.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/space_exploration/8va%20interpolation/interpolation_8va_E2_E36.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/space_exploration/8va%20interpolation/interpolation_8va_E2_E37.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/space_exploration/8va%20interpolation/interpolation_8va_E2_E38.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/space_exploration/8va%20interpolation/interpolation_8va_E2_E39.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/space_exploration/8va%20interpolation/interpolation_8va_E2_E310.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/space_exploration/8va%20interpolation/interpolation_8va_E2_E311.wav">
        </audio>
</div>
</div>

### Euclidean Neighborhood


Blues Driver - Chorus
![waveforms_BD-CH](https://user-images.githubusercontent.com/92285232/171494945-e023212a-fb90-4ca1-9b32-beff7e3c8b5c.png)

<div class="figure">
    <div align ="left">

        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/euclidean_distance/BD-CH-6/BD-CH-6-0_0.wav">
        </audio>
        
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/euclidean_distance/BD-CH-6/BD-CH-6-0_1.wav">
        </audio> 
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/euclidean_distance/BD-CH-6/BD-CH-6-0_2.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/euclidean_distance/BD-CH-6/BD-CH-6-0_3.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/euclidean_distance/BD-CH-6/BD-CH-6-0_4.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/euclidean_distance/BD-CH-6/BD-CH-6-0_5.wav">
        </audio>
        
</div>
</div>

Chorus-BluesDriver

![waveforms_CH-BD-6](https://user-images.githubusercontent.com/92285232/171496935-7fff14fc-0e1c-49b7-92e3-1c5a927df0b3.png)

<div class="figure">
    <div align ="left">

        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/euclidean_distance/CH-BD-6/CH-BD-6-00.wav">
        </audio>
        
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/euclidean_distance/CH-BD-6/CH-BD-6-01.wav">
        </audio> 
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/euclidean_distance/CH-BD-6/CH-BD-6-02.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/euclidean_distance/CH-BD-6/CH-BD-6-03.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/euclidean_distance/CH-BD-6/CH-BD-6-04.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/euclidean_distance/CH-BD-6/CH-BD-6-05.wav">
        </audio>
        
</div>
</div>


REAL FX

![waveformsPasados](https://user-images.githubusercontent.com/92285232/171496164-b700d098-4785-4978-8903-aa5e10d36da7.png)
![spectrogramsPasados](https://user-images.githubusercontent.com/92285232/171496207-44a1a8c2-b1e2-4107-899b-5a57238fb312.png)


<div class="figure">
    <div align ="left">

<audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/euclidean_distance/BD-CH-6-0.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/euclidean_distance/BD-CH-6-12.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/euclidean_distance/CH-BD-6-0.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/euclidean_distance/CH-BD-6-12.wav">
        </audio>
        
</div>
</div>

E2 Nearness

![E2_near](https://user-images.githubusercontent.com/92285232/171497441-9aa6ba90-a510-4190-84ea-1914270343d5.png)
![fft_E2](https://user-images.githubusercontent.com/92285232/171497487-23ea3aaa-0c01-4d90-93bc-f1b1bd7b6949.png)

<div class="figure">
    <div align ="left">

        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/euclidean_distance/E2_near/E2_near_0.wav">
        </audio>
        
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/euclidean_distance/E2_near/E2_near_1.wav">
        </audio> 
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/euclidean_distance/E2_near/E2_near_2.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/euclidean_distance/E2_near/E2_near_3.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/euclidean_distance/E2_near/E2_near_4.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/euclidean_distance/E2_near/E2_near_5.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/euclidean_distance/E2_near/E2_near_6.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/euclidean_distance/E2_near/E2_near_7.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/euclidean_distance/E2_near/E2_near_8.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/euclidean_distance/E2_near/E2_near_9.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/euclidean_distance/E2_near/E2_near_10.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/euclidean_distance/E2_near/E2_near_11.wav">
        </audio>
           <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/euclidean_distance/E2_near/E2_near_12.wav">
        </audio>
</div>
</div>

Fx-Chain

![waveforms_1-6-0](https://user-images.githubusercontent.com/92285232/171498552-07f966e1-5229-4533-aed3-e15ea253a94b.png)

<div class="figure">
    <div align ="left">

<audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/euclidean_distance/fx-chain-1-6-0/FX-Chain-1-6-0_0.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/euclidean_distance/fx-chain-1-6-0/FX-Chain-1-6-0_1.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/euclidean_distance/fx-chain-1-6-0/FX-Chain-1-6-0_2.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/euclidean_distance/fx-chain-1-6-0/FX-Chain-1-6-0_3.wav">
        </audio>
         <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/euclidean_distance/fx-chain-1-6-0/FX-Chain-1-6-0_4.wav">
        </audio>
         <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/euclidean_distance/fx-chain-1-6-0/FX-Chain-1-6-0_5.wav">
        </audio>
        
</div>
</div>


Real Chain

<div class="figure">
    <div align ="left">
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="https://github.com/mezaga/guitar_VAE/raw/main/euclidean_distance/FXChain1-6-0.wav">
        </audio>
    </div>
    </div>
