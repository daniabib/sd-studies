*Model:* paprika-mellucy-v1


## Video-01:

### 01-control-random:

an cel animation of lucyliu in the style by (pprkstltkn:1.3),with short black hair and wearing a red reagged blouse and black sportive pants
Negative prompt: two head, (ugly), duplicate, morbid, out of frame, (poorly drawn hands), (poorly drawn face), nsfw, mutation, deformed, blurry, bad anatomy, bad proportions, extra limbs, cloned face, disfigured, gross proportions, malformed limbs, long neck, ((horns)), cg, 3d
Steps: 20, Sampler: Euler, CFG scale: 8, Seed: 1062019380, Size: 640x1064, Model hash: 13fa89b815, Model: paprika-mellucy-v2, Denoising strength: 0.65, Mask blur: 4, ControlNet-0 Enabled: True, ControlNet-0 Module: depth, ControlNet-0 Model: control_depth-fp16 [400750f6], ControlNet-0 Weight: 1, ControlNet-0 Guidance Start: 0, ControlNet-0 Guidance End: 1
- Aumentar o número de steps para o próximo
- Depth

### 02-control-random
lucyliu wearing a (((panda jacket))) in the aesthetic of pprkstltkn style, serious face
Negative prompt: two head, (ugly), duplicate, morbid, out of frame, (poorly drawn hands), (poorly drawn face), nsfw, mutation, deformed, blurry, bad anatomy, bad proportions, extra limbs, cloned face, disfigured, gross proportions, malformed limbs, long neck, ((horns)), cg, 3d
Steps: 30, Sampler: Euler, CFG scale: 8, Seed: 2964443191, Size: 640x960, Model hash: 13fa89b815, Model: paprika-mellucy-v2, Denoising strength: 0.65, Mask blur: 4, ControlNet-0 Enabled: True, ControlNet-0 Module: depth, ControlNet-0 Model: control_depth-fp16 [400750f6], ControlNet-0 Weight: 1, ControlNet-0 Guidance Start: 0, ControlNet-0 Guidance End: 1, ControlNet-1 Enabled: True, ControlNet-1 Module: canny, ControlNet-1 Model: control_canny-fp16 [e3fe7712], ControlNet-1 Weight: 0.3, ControlNet-1 Guidance Start: 0, ControlNet-1 Guidance End: 1
- Aumentei step para 30.
- Testando prompt mais direcionado. 
- Adicionei canny a controlnet.

# 03-control-fixseed
an cel animation of (lucyliu:1.2) in the aesthetic of (pprkstltkn:1.4) style, serious face
Negative prompt: cataracts, weird eyes,two head, (ugly), duplicate, morbid, out of frame, (poorly drawn hands), (poorly drawn face), nsfw, mutation, deformed, blurry, bad anatomy, bad proportions, extra limbs, cloned face, disfigured, gross proportions, malformed limbs, long neck, ((horns)),
Steps: 30, Sampler: Euler, CFG scale: 8, Seed: 3947546186, Size: 704x1064, Model hash: 13fa89b815, Model: paprika-mellucy-v2, Denoising strength: 0.75, Mask blur: 4, ControlNet-0 Enabled: True, ControlNet-0 Module: canny, ControlNet-0 Model: control_canny-fp16 [e3fe7712], ControlNet-0 Weight: 0.3, ControlNet-0 Guidance Start: 0, ControlNet-0 Guidance End: 1, ControlNet-1 Enabled: True, ControlNet-1 Module: normal_map, ControlNet-1 Model: control_normal-fp16 [63f96f7c], ControlNet-1 Weight: 0.5, ControlNet-1 Guidance Start: 0, ControlNet-1 Guidance End: 1
- Canny:0.3 + Normal Map:0.5
- Estilo mais animação pastelado


### TODO
Testar com outros samplers 

# DREAMSAM
# 01-img2img-fixedseed
(samdoesart:1.1) (dreamlikeart:1) full body portrait of a beautiful (lucyliu:1.3) person dancing with a red shirt and a black sports pants, short hair, masterpiece, intense shadows, ambient light, illustration, (thick outlines:1.2), cartoon, highres, drawn by Inoue Takehiko, (Yoji Shinkawa:0.9), Jakub Rozalski, (kuvshinov:1)
Negative prompt: bag, backpack, weapon, guns, (ugly:1.5), (duplicate:1.3), (morbid:1.2), (mutilated:1.2), (mutation), [out of frame], (extra fingers:1.2), (more than two arms), (more than two legs), (missing arms), (missing legs), (poorly drawn hands:1.3), (poorly drawn face:1.3), (deformed:1.2), blurry, (bad anatomy), (bad proportions), (disfigured:1.3), extra limbs, (malformed limbs), mutated hands, (fused fingers), (makeup)
Steps: 30, Sampler: Euler, CFG scale: 9, Seed: 154910064, Size: 704x1072, Model hash: 13fa89b815, Model: paprika-mellucy-v2, Denoising strength: 0.5, Mask blur: 4