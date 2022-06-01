
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
            <source src="folder/dataset_examples/Bridge_6-0.wav">
        </audio>
        
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="folder/dataset_examples/bridge_Middle_6-0.wav">
        </audio> 
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="folder/dataset_examples/middle_6-0.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="folder/dataset_examples/Middle_Neck6-0.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="folder/dataset_examples/Neck_6-0.wav">
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
            <source src="folder/dataset_examples/TubeScreamer_6-0.wav">
        </audio>
        
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="folder/dataset_examples/BluesDriver_6-0.wav">
        </audio> 
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="folder/dataset_examples/RAT_6-0.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="folder/dataset_examples/Chorus_6-0.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="folder/dataset_examples/Phaser_6-0.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="folder/dataset_examples/Flanger_6-0.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="folder/dataset_examples/Tape_echo6-0.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="folder/dataset_examples/SweepEcho_6-0.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="folder/dataset_examples/DigitalDlay6-0.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="folder/dataset_examples/Hall_Reverb6-0.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="folder/dataset_examples/Plate_Reverb6-0.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="folder/dataset_examples/Spring_Reverb_6-0.wav">
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
            <source src="folder/dataset_examples/TubeScreamer_6-0.wav">
        </audio>
        
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="folder/dataset_examples/BluesDriver_6-0.wav">
        </audio> 
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="folder/dataset_examples/RAT_6-0.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="folder/dataset_examples/Chorus_6-0.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="folder/dataset_examples/Phaser_6-0.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="folder/dataset_examples/Flanger_6-0.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="folder/dataset_examples/Tape_echo6-0.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="folder/dataset_examples/SweepEcho_6-0.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="folder/dataset_examples/DigitalDlay6-0.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="folder/dataset_examples/Hall_Reverb6-0.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="folder/dataset_examples/Plate_Reverb6-0.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="folder/dataset_examples/Spring_Reverb_6-0.wav">
        </audio>
</div>
</div>
