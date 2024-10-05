from ursina import * 
from ursina.prefabs.first_person_controller import FirstPersonController
from perlin_noise import PerlinNoise

这个是导入ursina库和柏林噪声的代码

grass_texture = load_texture('assets/grass_block.png')
stone_texture = load_texture('assets/stone_block.png')
brick_texture = load_texture('assets/brick_block.png')
dirt_texture = load_texture('assets/dirt_block.png')

导入方块
sky_texture = load_texture('assets/skybox.png')

导入天空
arm_texture = load_texture('assets/arm_texture.png')

导入手臂
punch_sound = Audio('assets/punch_sound.wav',loop=False,autoplay=False)

导入声音
background_sound =Audio('music/background.flac',autoplay=True)

背景音乐（可自己添加）

block_pick = 1

默认使用放置草方块


代码来自抖音：侯老师编程

上传是为了方便新手可以直接拿代码，避免三分钟热度
