
# VAE GUITAR

From all the possible notes of an electric guitar processed by ten different effects and different configurations, we employed a Variational Autoencoder to generate audio from the resultant latent space and compare them with a similar analog fx chain. The intention of the present research is to sum up to the outgoing interest to explore the relationships between deep learning models and timbrical variations. The main goal of this research is to propose another perspective of linking analog guitar effects for timbre generation outside the active emulation/recognition studies.

![Guitarra](https://user-images.githubusercontent.com/31640735/170167851-d74f1017-5f94-45d9-8f28-78c10a3f8668.JPG)

### FXs

1. Blue Driver
2. Chorus
3. Clean
4. Digital Delay
5. Flanger
6. Phaser
7. RAT
8. Sweep Echo
9. Tape Echo
10. Tube Screamer

### Reconstruction

<div class="figure">
    <div align ="left">

        <audio controls style="width: 20%; padding: 0.5%">
            <source src="folder/rec_DigitalDlay.wav">
        </audio>
        
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="folder/rec_bluesdriver.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="folder/rec_chorus.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="folder/rec_clean.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="folder/rec_flanger.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="folder/rec_phaser.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="folder/rec_rat.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="folder/rec_sweetEcho.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="folder/rec_tapeEcho.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="folder/rec_tubescreamer.wav">
        </audio>
</div>
</div>

### Latent Space
![latent_space3D](https://user-images.githubusercontent.com/31640735/170166020-c0ea065d-5237-4534-982e-00393a2cc890.png)

### Latent Space Interpolations

![latent_interpolation](https://user-images.githubusercontent.com/31640735/170180602-5aab303a-35c3-4504-9f6a-371ca5448c8a.png)


![interpolation_latentspace_stft](https://user-images.githubusercontent.com/31640735/170180263-49e1e121-0350-4dcf-a731-34eeb23f1d2d.png)



<div class="figure">
    <div align ="left">

        <audio controls style="width: 20%; padding: 0.5%">
            <source src="folder/inter_1.wav">
        </audio>
        
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="folder/inter_2.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="folder/inter_3.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="folder/inter_4.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="folder/inter_5.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="folder/inter_6.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="folder/inter_7.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="folder/inter_8.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="folder/inter_9.wav">
        </audio>
        <audio controls style="width: 20%; padding: 0.5%">
            <source src="folder/inter_10.wav">
        </audio>
</div>
</div>

### Resultados

