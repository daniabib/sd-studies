## Test 1:
*Processo*: [Fast-Dreambooth](https://github.com/TheLastBen/fast-stable-diffusion)

*Modelo base:* [Protogenv2.2](https://civitai.com/models/3627/protogen-v22-anime-official-release) 

*Dataset*: melprsn-v1

*Dataset size*: 
* 22 fotos:
    * 6 corpo
    * 10 médio
    * 6 rosto
* Fundo cinza


## Test 2:
*Processo*: [Fast-Dreambooth](https://github.com/TheLastBen/fast-stable-diffusion)

*Modelo base:* v1-5-pruned-emaonly.ckpt

*Dataset*: melprsn-v2
*Dataset size*: 
* 46 fotos:
    * 16 corpo
    * 14 médio
    * 16 rosto
* Fundo cinza e removido (misturados)

*Regularization*: None

*CKPT out name (session name)*: melprsn-sd15-v1 

*UNet_Training_Steps:* 1500 + 1000 + 1000 + 1000 + 1000

*UNet_Learning_Rate:* 2e-6

*Text_Encoder_Training_Steps:* 350 + 0 + 0 + 0 + 50

### Prompts test:
1. melprsn
1. melprsn person
1. melprsn woman
1. photo of a melprsn person
1. photo of a melprsn woman
1. an (anime) photo of a melprsn woman wearing a ragged red plain blouse, in the (style by makoto shinkai) Negative prompt: worst quality, (low quality:1.4), blurry, bad anatomy, bad proportions, ((3d))
1. 


## Test 3:
*Processo*: [Fast-Dreambooth](https://github.com/TheLastBen/fast-stable-diffusion)

*Modelo base:* https://huggingface.co/prompthero/openjourney

*Dataset*: melprsn-v2
*Dataset size*: 
* 46 fotos:
    * 16 corpo
    * 14 médio
    * 16 rosto
* Fundo cinza e removido (misturados)

*Regularization*: None

*CKPT out name (session name)*: melprsn-openjourney-v1 

*UNet_Training_Steps:* 5000

*UNet_Learning_Rate:* 1e-6

*Text_Encoder_Training_Steps:* 350

## Test 4:
*Processo*: [Fast-Dreambooth](https://github.com/TheLastBen/fast-stable-diffusion)

*Modelo base:* v1-5

*Dataset*: melghosttkn-v1
*Dataset size*: 
* 46 fotos MEL:
    * 16 corpo
    * 14 médio
    * 16 rosto
* Fundo cinza e removido (misturados)
+
* 92 fotos GHOST-SHELL:
    * selecionadas por KNN (selectimages)

*Regularization*: None

*CKPT out name (session name)*: melprsn-fastghost-v1 

*UNet_Training_Steps:* 1500 + 1000 + 1000 (parecenendo anime generico) + 2000 + 3000

*UNet_Learning_Rate:* 2e-6

*Text_Encoder_Training_Steps:* 350 + 100 + 100 + 0 

## Test 4:
*Processo*: [Fast-Dreambooth](https://github.com/TheLastBen/fast-stable-diffusion)

*Modelo base:* v1-5

*Dataset*: melghosttkn-v1
*Dataset size*: 
* 46 fotos MEL:
    * 16 corpo
    * 14 médio
    * 16 rosto
* Fundo cinza e removido (misturados)
+
* 92 fotos GHOST-SHELL:
    * selecionadas por KNN (selectimages)

*Regularization*: None

*CKPT out name (session name)*: melprsn-fastghost-v1 

*UNet_Training_Steps:* 1500 + 1000 + 1000 (parecenendo anime generico) + 2000 + 3000

*UNet_Learning_Rate:* 2e-6

*Text_Encoder_Training_Steps:* 350 + 100 + 100 + 0 

## Test 4:
*Processo*: [Fast-Dreambooth](https://github.com/TheLastBen/fast-stable-diffusion)

*Modelo base:* v1-5

*Dataset*: melghosttkn-v1
*Dataset size*: 
* 46 fotos MEL:
    * 16 corpo
    * 14 médio
    * 16 rosto
* Fundo cinza e removido (misturados)
+
* 92 fotos GHOST-SHELL:
    * selecionadas por KNN (selectimages)

*Regularization*: None

*CKPT out name (session name)*: melprsn-fastghost-v1 

*UNet_Training_Steps:* 9500 + 3000

*UNet_Learning_Rate:* 2e-6

*Text_Encoder_Training_Steps:* 500

*Offset_Noise:* True

an anime cel animation of an (melghosttkn woman) wearing a ragged red plain blouse
Negative prompt: (((duplicate))), ((morbid)), ((mutilated)), [out of frame], extra fingers, mutated hands, ((poorly drawn hands)), ((poorly drawn face)), (((mutation))), (((deformed))), ((ugly)), blurry, ((bad anatomy)), (((bad proportions))), ((extra limbs)), cloned face, (((disfigured))), out of frame, ugly, extra limbs, (bad anatomy), gross proportions, (malformed limbs), ((missing arms)), ((missing legs)), (((extra arms))), (((extra legs))), mutated hands, (fused fingers), (too many fingers), (((long neck)))
Steps: 35, Sampler: Euler a, CFG scale: 7, Seed: 3673725418, Size: 512x512, Model hash: ddf1827974, Model: melprsn-fastghost-v1

 Script

a portrait of (melghosttkn woman) wearing a ragged red plain blouse with anime style
Negative prompt: (((duplicate))), ((morbid)), ((mutilated)), [out of frame], extra fingers, mutated hands, ((poorly drawn hands)), ((poorly drawn face)), (((mutation))), (((deformed))), ((ugly)), blurry, ((bad anatomy)), (((bad proportions))), ((extra limbs)), cloned face, (((disfigured))), out of frame, ugly, extra limbs, (bad anatomy), gross proportions, (malformed limbs), ((missing arms)), ((missing legs)), (((extra arms))), (((extra legs))), mutated hands, (fused fingers), (too many fingers), (((long neck)))
Steps: 35, Sampler: Euler a, CFG scale: 7, Seed: 3817935387, Size: 512x512, Model hash: 7ebf160cd8, Model: melprsn-fastghost-v2


## Test 5:
*Processo*: [Fast-Dreambooth](https://github.com/TheLastBen/fast-stable-diffusion)

*Modelo base:* v1-5

*Dataset*: melprsn-v1
*Dataset size*: 
* 46 fotos MEL:
    * 16 corpo
    * 14 médio
    * 16 rosto
* Fundo cinza e removido (misturados)

*Regularization*: None

*CKPT out name (session name)*: melprsn-anything-v1 

*UNet_Training_Steps:* 3220 + 1500 + 3000

*UNet_Learning_Rate:* 2e-6

*Text_Encoder_Training_Steps:* 400 + 0 + 100

*Offset_Noise:* True


# Prompts to test:
1. melprsn
1. melprsn person
1. melprsn woman
1. photo of a melprsn person
1. photo of a melprsn woman
1. an (anime) photo of a melprsn woman wearing a ragged red plain blouse, in the (style by makoto shinkai) Negative prompt: worst quality, (low quality:1.4), blurry, bad anatomy, bad proportions, ((3d))
1.  (urushisato:1.0), (OVA:1.4) cel animation of (melprsn woman) style, painting, best quality, masterpiece, <lora:urushisato_v15:1.0>
Negative prompt: two head, (ugly), duplicate, morbid, out of frame, (poorly drawn hands), (poorly drawn face), nsfw, mutation, deformed, blurry, bad anatomy, bad proportions, extra limbs, cloned face, disfigured, gross proportions, malformed limbs, long neck, ((horns))
Steps: 50, Sampler: Euler, CFG scale: 7, Seed: 590708897, Size: 512x512, Model hash: b0c46ec815, Model: melprsn-v1
1. (urushisato:1.0), (OVA:1.4) anime cel animation of melprsn woman, best quality, masterpiece, <lora:urushisato_v15:1.0>
Negative prompt: two head, (ugly), duplicate, morbid, out of frame, (poorly drawn hands), (poorly drawn face), nsfw, mutation, deformed, blurry, bad anatomy, bad proportions, extra limbs, cloned face, disfigured, gross proportions, malformed limbs, long neck, ((horns))
Steps: 25, Sampler: Euler, CFG scale: 7, Seed: 590708897, Size: 512x512, Model hash: b0c46ec815, Model: melprsn-v1


## Test 5:
*Processo*: [Niko's Dreambooth](https://github.com/gammagec/Dreambooth-SD-optimized)

*Modelo base:* [v1-5-pruned.ckpt](https://huggingface.co/runwayml/stable-diffusion-v1-5)

*Dataset*: melprsn-v1, paprika
tokens: melprsntkn, pprkstl
*Dataset size*: 
* 46 fotos MEL:
    * 16 corpo
    * 14 médio
    * 16 rosto
    * Fundo cinza e removido (misturados)
* 99 fotos Paprika


*Regularization*: 
* 10k `woman`
* 10k `aesthetic`

*Changes in configs/stable-diffusion/configs/v1-finteune_unfrozen.yaml*:
```yaml
data:
  params:
    train:
      params:
        repeats: 70
    reg:
      params:
        repeats: 1
        
    validation:
      params:
        repeats: 1
```

*Changes in workspace/Dreambooth-SD-optimized/ldm/data/personalized.py*:
```python
class PersonalizedBase(Dataset):
    def __init__(self,
                 data_root,
                 size=None,
                 repeats=100,
                 interpolation="bicubic",
                 flip_p=0.0, #set flip to 0
                 set="train",
                 placeholder_token="dog",
                 per_image_tokens=False,
                 center_crop=False,
                 mixing_prob=0.25,
                 coarse_class_text=None,
                 reg = False
                 ):
```

*CKPT out name (session name)*: melprsn-anything-v1 

*UNet_Training_Steps:* 10150 -> (99 + 46) * 70

*UNet_Learning_Rate:* 2e-6

*Text_Encoder_Training_Steps:* 400 + 0 + 100

*Offset_Noise:* True

Command line arguments
```bash
python main.py --base configs/stable-diffusion/v1-finetune_unfrozen.yaml 
                -t 
                --actual_resume models/v1-5-pruned.ckpt
                -n mel-paprika-nikos-10150 
                --gpus 0, 
                --data_root training-images
                --reg_data_root reg-images
                --token melprsntkn
                --class_word woman
                --max_training_steps 10150
```

# Prompts to test:
1. melprsn
1. melprsn person
1. melprsn woman
1. photo of a melprsn person
1. photo of a melprsn woman
1. an (anime) photo of a melprsn woman wearing a ragged red plain blouse, in the (style by makoto shinkai) Negative prompt: worst quality, (low quality:1.4), blurry, bad anatomy, bad proportions, ((3d))
1.  (urushisato:1.0), (OVA:1.4) cel animation of (melprsn woman) style, painting, best quality, masterpiece, <lora:urushisato_v15:1.0>
Negative prompt: two head, (ugly), duplicate, morbid, out of frame, (poorly drawn hands), (poorly drawn face), nsfw, mutation, deformed, blurry, bad anatomy, bad proportions, extra limbs, cloned face, disfigured, gross proportions, malformed limbs, long neck, ((horns))
Steps: 50, Sampler: Euler, CFG scale: 7, Seed: 590708897, Size: 512x512, Model hash: b0c46ec815, Model: melprsn-v1
1. (urushisato:1.0), (OVA:1.4) anime cel animation of melprsn woman, best quality, masterpiece, <lora:urushisato_v15:1.0>
Negative prompt: two head, (ugly), duplicate, morbid, out of frame, (poorly drawn hands), (poorly drawn face), nsfw, mutation, deformed, blurry, bad anatomy, bad proportions, extra limbs, cloned face, disfigured, gross proportions, malformed limbs, long neck, ((horns))
Steps: 25, Sampler: Euler, CFG scale: 7, Seed: 590708897, Size: 512x512, Model hash: b0c46ec815, Model: melprsn-v1

## Test 7:
*Processo*: [Fast-Dreambooth](https://github.com/TheLastBen/fast-stable-diffusion)

*Modelo base:* AnythingV3.0

*Dataset*: melprsn-v3
*Dataset size*: 
* 20 fotos MEL:
    * 16 corpo
    * 14 médio
    * 16 rosto
* Fundo cinza e removido (misturados)

*Regularization*: 300 woman anything

*CKPT out name (session name)*: melprsn-prestyle-v1 

*UNet_Training_Steps:* 2000

*UNet_Learning_Rate:* 2e-6

*Text_Encoder_Training_Steps:* 400 

*Offset_Noise:* False


## Test 8:
*Processo*: [Fast-Dreambooth](https://github.com/TheLastBen/fast-stable-diffusion)

*Modelo base:* AnythingV3.0

*Dataset*: melprsn-v3
*Dataset size*: 
* 20 fotos MEL:
    * 16 corpo
    * 14 médio
    * 16 rosto
* Fundo cinza e removido (misturados)

*Regularization*: 300 woman anything

*CKPT out name (session name)*: melprsn-prestyle-v1 

*UNet_Training_Steps:* 19320

*UNet_Learning_Rate:* 1e-6

*Text_Encoder_Training_Steps:* 600

Text_Encoder_Concept_Training_Steps= 300

Offset_Noise= True

*Offset_Noise:* True

TEST 8 Funcionando interessante assim:

an cel animation of a (melprsn:1.2) woman standing with red painting in her eyes, in the (style by pprkstltkn)
Negative prompt: (3d), (cgi), two head, (ugly), duplicate, morbid, out of frame, (poorly drawn hands), (poorly drawn face), nsfw, mutation, deformed, blurry, bad anatomy, bad proportions, extra limbs, cloned face, disfigured, gross proportions, malformed limbs, long neck, ((horns))
Steps: 30, Sampler: Euler a, CFG scale: 7, Seed: 3390913259, Size: 896x1072, Model hash: 2f23e688b6, Model: mel-paprika-v1, Denoising strength: 0.7, Mask blur: 4, ControlNet-0 Enabled: True, ControlNet-0 Module: canny, ControlNet-0 Model: control_canny-fp16 [e3fe7712], ControlNet-0 Weight: 0.55, ControlNet-0 Guidance Start: 0, ControlNet-0 Guidance End: 1, ControlNet-1 Enabled: True, ControlNet-1 Module: depth, ControlNet-1 Model: control_depth-fp16 [400750f6], ControlNet-1 Weight: 0.8, ControlNet-1 Guidance Start: 0, ControlNet-1 Guidance End: 1


an cel animation of a (melprsn:1.2) woman standing with red painting in her eyes, in the (style by pprkstltkn)
Negative prompt: (3d), (cgi), two head, (ugly), duplicate, morbid, out of frame, (poorly drawn hands), (poorly drawn face), nsfw, mutation, deformed, blurry, bad anatomy, bad proportions, extra limbs, cloned face, disfigured, gross proportions, malformed limbs, long neck, ((horns))
Steps: 30, Sampler: Euler, CFG scale: 7, Seed: 3390913259, Size: 896x1072, Model hash: 2f23e688b6, Model: mel-paprika-v1, Denoising strength: 0.7, Mask blur: 4, Decode prompt: photo a melprsn woman, Decode negative prompt: , Decode CFG scale: 1, Decode steps: 30, Randomness: 0, Sigma Adjustment: True, ControlNet-0 Enabled: True, ControlNet-0 Module: canny, ControlNet-0 Model: control_canny-fp16 [e3fe7712], ControlNet-0 Weight: 0.55, ControlNet-0 Guidance Start: 0, ControlNet-0 Guidance End: 1, ControlNet-1 Enabled: True, ControlNet-1 Module: depth, ControlNet-1 Model: control_depth-fp16 [400750f6], ControlNet-1 Weight: 0.8, ControlNet-1 Guidance Start: 0, ControlNet-1 Guidance End: 1


# Test 9:
## First: Paprika Style
*Processo*: [Fast-Dreambooth](https://github.com/TheLastBen/fast-stable-diffusion)

*Modelo base:* AnythingV3.0

*Dataset*: paprika-512
*Dataset size*: 
* 275 screens

*Regularization*: None

*CKPT out name (session name)*: paprika-anything-v1 

*UNet_Training_Steps:* 20000

*UNet_Learning_Rate:* 1e-6

*Text_Encoder_Training_Steps:* 600 

*Text_Encoder_Concept_Training_Steps:* 300

*Offset_Noise:* True

*Processo*: [Fast-Dreambooth](https://github.com/TheLastBen/fast-stable-diffusion)

## Then: MEL
*Modelo base:* AnythingV3.0

*Token as:* lucyliu

*Dataset*: melprsn-v3
*Dataset size*: 
* 20 fotos MEL:
    * 16 corpo
    * 14 médio
    * 16 rosto
* Fundo cinza e removido (misturados)

*Regularization*: 2k person paprika-anything-v1

*CKPT out name (session name)*: paprika-mel-v1 

*UNet_Training_Steps:* 1000

*UNet_Learning_Rate:* 2e-6

*Text_Encoder_Training_Steps:* 350 

*Offset_Noise:* False

Testar com:
 Script

an cel animation of a (melprsn:1.2) person wearing a red reagged blouse and black sportive pants with red painting in her eyes, in the (style by pprkstltkn)
Negative prompt: two head, (ugly), duplicate, morbid, out of frame, (poorly drawn hands), (poorly drawn face), nsfw, mutation, deformed, blurry, bad anatomy, bad proportions, extra limbs, cloned face, disfigured, gross proportions, malformed limbs, long neck, ((horns))
Steps: 35, Sampler: DPM++ SDE Karras, CFG scale: 7, Seed: 1670905199, Size: 512x512, Model hash: 6bea5a4fad, Model: paprika-mel-v1
 Script

an cel animation of a (melprsn:1.3) person holding a katana blade and wearing a red reagged blouse and sportive black pants with red painting in her eyes, in the style by (pprkstltkn:1.1)
Negative prompt: two head, (ugly), duplicate, morbid, out of frame, (poorly drawn hands), (poorly drawn face), nsfw, mutation, deformed, blurry, bad anatomy, bad proportions, extra limbs, cloned face, disfigured, gross proportions, malformed limbs, long neck, ((horns))
Steps: 35, Sampler: Euler a, CFG scale: 7, Seed: 3682908760, Size: 512x768, Model hash: e2398cf2ec, Model: paprika-mel-v1

Rosto:
an anime character design portrait of a (melprsn:1) person smiling and with red painting in her eyes, in the style by (pprkstltkn:1.1)
Negative prompt: red background, two head, (ugly), duplicate, morbid, out of frame, (poorly drawn hands), (poorly drawn face), nsfw, mutation, deformed, blurry, bad anatomy, bad proportions, extra limbs, cloned face, disfigured, gross proportions, malformed limbs, long neck, ((horns))
Steps: 35, Sampler: DPM++ 2M, CFG scale: 7, Seed: 2198050582, Size: 512x768, Model hash: e2398cf2ec, Model: paprika-mel-v1


Img2Img
an cel animation of a (melprsn:1.2) person holding a katana blade and wearing a red reagged blouse and black sportive pants with red painting in her eyes, in the style by (pprkstltkn:1.4)
Negative prompt: two head, (ugly), duplicate, morbid, out of frame, (poorly drawn hands), (poorly drawn face), nsfw, mutation, deformed, blurry, bad anatomy, bad proportions, extra limbs, cloned face, disfigured, gross proportions, malformed limbs, long neck, ((horns))
Steps: 30, Sampler: DPM++ 2M Karras, CFG scale: 8, Seed: 3344750449, Size: 512x632, Model hash: 6f7617ad87, Model: paprika-mel-v1, Denoising strength: 0.75, Mask blur: 4, ControlNet-0 Enabled: True, ControlNet-0 Module: canny, ControlNet-0 Model: control_canny-fp16 [e3fe7712], ControlNet-0 Weight: 0.35, ControlNet-0 Guidance Start: 0, ControlNet-0 Guidance End: 1, ControlNet-1 Enabled: True, ControlNet-1 Module: normal_map, ControlNet-1 Model: control_normal-fp16 [63f96f7c], ControlNet-1 Weight: 0.5, ControlNet-1 Guidance Start: 0, ControlNet-1 Guidance End: 1


IMAGE2IMAGE BATCHS:

1. an cel animation of a (melprsn:1.5) person in the style by (pprkstltkn:1.3), and with red painting in her eyes and wearing a red reagged blouse and short black hair, adult woman
Negative prompt: two head, (ugly), duplicate, morbid, out of frame, (poorly drawn hands), (poorly drawn face), nsfw, mutation, deformed, blurry, bad anatomy, bad proportions, extra limbs, cloned face, disfigured, gross proportions, malformed limbs, long neck, ((horns)), cg, 3d
Steps: 35, Sampler: Euler, CFG scale: 8, Seed: 1087266718, Size: 512x512, Model hash: e2398cf2ec, Model: paprika-mel-v1