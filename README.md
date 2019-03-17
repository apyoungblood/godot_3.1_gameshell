# godot_3.1_gameshell

An export template for Godot Engine v 3.1 stable built on ClockworkPi Gameshell

Compiled on ClockworkPi Gameshell using the following command:

`scons platform=x11 use_llvm=yes tools=no target=release bits=32 &`

_\*This process took about 2 hours to run on device_

Running the exported project binaries with debugging gave the following errors along with distorted but playing sound and input that worked, but no visuals following the Godot Engine splash screen:

```
cpi@clockworkpi:~/downloads/godot_3.1/platformer2d$ ./Platformer_2D.x86 --video-driver GLES2 --verbose
XInput: Refreshing devices.
XInput: No touch devices found.
Detecting GPUs, set DRI_PRIME in the environment to override GPU detection logic.
X Error of failed request:  GLXBadFBConfig
  Major opcode of failed request:  155 (GLX)
  Minor opcode of failed request:  34 ()
  Serial number of failed request:  25
  Current serial number in output stream:  22
X Error of failed request:  GLXBadFBConfig
  Major opcode of failed request:  155 (GLX)
  Minor opcode of failed request:  34 ()
  Serial number of failed request:  25
  Current serial number in output stream:  22
Only one GPU found, using default.
XcursorGetTheme could not get cursor theme
Using GLES2 video driver
OpenGL ES 2.0 Renderer: Mali400
error: lima_blit not implemented

error: lima_blit not implemented

error: lima_blit not implemented

error: lima_blit not implemented

error: lima_blit not implemented

error: lima_blit not implemented

error: lima_blit not implemented

error: lima_blit not implemented

error: lima_blit not implemented

error: lima_blit not implemented

error: lima_blit not implemented

error: lima_blit not implemented

ERROR: _gl_debug_print: GL ERROR: Source: OpenGL        Type: Error     ID: 2   Severity: High  Message: GL_INVALID_OPERATION in glTexImage2D(bad target for texture)
   At: drivers/gles2/rasterizer_gles2.cpp:134.
ERROR: _gl_debug_print: GL ERROR: Source: OpenGL        Type: Error     ID: 2   Severity: High  Message: GL_INVALID_OPERATION in glTexImage2D(bad target for texture)
   At: drivers/gles2/rasterizer_gles2.cpp:134.
ERROR: _gl_debug_print: GL ERROR: Source: OpenGL        Type: Error     ID: 2   Severity: High  Message: GL_INVALID_OPERATION in glTexImage2D(bad target for texture)
   At: drivers/gles2/rasterizer_gles2.cpp:134.
ERROR: _gl_debug_print: GL ERROR: Source: OpenGL        Type: Error     ID: 2   Severity: High  Message: GL_INVALID_OPERATION in glTexImage2D(bad target for texture)
   At: drivers/gles2/rasterizer_gles2.cpp:134.
ERROR: _gl_debug_print: GL ERROR: Source: OpenGL        Type: Error     ID: 2   Severity: High  Message: GL_INVALID_OPERATION in glTexImage2D(bad target for texture)
   At: drivers/gles2/rasterizer_gles2.cpp:134.
ERROR: _gl_debug_print: GL ERROR: Source: OpenGL        Type: Error     ID: 2   Severity: High  Message: GL_INVALID_OPERATION in glTexImage2D(bad target for texture)
   At: drivers/gles2/rasterizer_gles2.cpp:134.
ERROR: _gl_debug_print: GL ERROR: Source: OpenGL        Type: Error     ID: 2   Severity: High  Message: GL_INVALID_OPERATION in glTexImage2D(bad target for texture)
   At: drivers/gles2/rasterizer_gles2.cpp:134.
ERROR: _gl_debug_print: GL ERROR: Source: OpenGL        Type: Error     ID: 2   Severity: High  Message: GL_INVALID_OPERATION in glTexImage2D(bad target for texture)
   At: drivers/gles2/rasterizer_gles2.cpp:134.
ERROR: _gl_debug_print: GL ERROR: Source: OpenGL        Type: Error     ID: 2   Severity: High  Message: GL_INVALID_OPERATION in glTexImage2D(bad target for texture)
   At: drivers/gles2/rasterizer_gles2.cpp:134.
ERROR: _gl_debug_print: GL ERROR: Source: OpenGL        Type: Error     ID: 2   Severity: High  Message: GL_INVALID_OPERATION in glTexImage2D(bad target for texture)
   At: drivers/gles2/rasterizer_gles2.cpp:134.
ERROR: _gl_debug_print: GL ERROR: Source: OpenGL        Type: Error     ID: 2   Severity: High  Message: GL_INVALID_OPERATION in glTexImage2D(bad target for texture)
   At: drivers/gles2/rasterizer_gles2.cpp:134.
ERROR: _gl_debug_print: GL ERROR: Source: OpenGL        Type: Error     ID: 2   Severity: High  Message: GL_INVALID_OPERATION in glTexImage2D(bad target for texture)
   At: drivers/gles2/rasterizer_gles2.cpp:134.
ERROR: _gl_debug_print: GL ERROR: Source: OpenGL        Type: Error     ID: 2   Severity: High  Message: GL_INVALID_OPERATION in glTexImage2D(bad target for texture)
   At: drivers/gles2/rasterizer_gles2.cpp:134.
ERROR: _gl_debug_print: GL ERROR: Source: OpenGL        Type: Error     ID: 2   Severity: High  Message: GL_INVALID_OPERATION in glTexImage2D(bad target for texture)
   At: drivers/gles2/rasterizer_gles2.cpp:134.
ERROR: _gl_debug_print: GL ERROR: Source: OpenGL        Type: Error     ID: 2   Severity: High  Message: GL_INVALID_OPERATION in glTexImage2D(bad target for texture)
   At: drivers/gles2/rasterizer_gles2.cpp:134.
ERROR: _gl_debug_print: GL ERROR: Source: OpenGL        Type: Error     ID: 2   Severity: High  Message: GL_INVALID_OPERATION in glTexImage2D(bad target for texture)
   At: drivers/gles2/rasterizer_gles2.cpp:134.
ERROR: _gl_debug_print: GL ERROR: Source: OpenGL        Type: Error     ID: 2   Severity: High  Message: GL_INVALID_OPERATION in glTexImage2D(bad target for texture)
   At: drivers/gles2/rasterizer_gles2.cpp:134.
ERROR: _gl_debug_print: GL ERROR: Source: OpenGL        Type: Error     ID: 2   Severity: High  Message: GL_INVALID_OPERATION in glTexImage2D(bad target for texture)
   At: drivers/gles2/rasterizer_gles2.cpp:134.
ERROR: _gl_debug_print: GL ERROR: Source: OpenGL        Type: Error     ID: 2   Severity: High  Message: GL_INVALID_OPERATION in glTexImage2D(bad target for texture)
   At: drivers/gles2/rasterizer_gles2.cpp:134.
ERROR: _gl_debug_print: GL ERROR: Source: OpenGL        Type: Error     ID: 2   Severity: High  Message: GL_INVALID_OPERATION in glTexImage2D(bad target for texture)
   At: drivers/gles2/rasterizer_gles2.cpp:134.
ERROR: _gl_debug_print: GL ERROR: Source: OpenGL        Type: Error     ID: 2   Severity: High  Message: GL_INVALID_OPERATION in glTexImage2D(bad target for texture)
   At: drivers/gles2/rasterizer_gles2.cpp:134.
ERROR: _gl_debug_print: GL ERROR: Source: OpenGL        Type: Error     ID: 2   Severity: High  Message: GL_INVALID_OPERATION in glTexImage2D(bad target for texture)
   At: drivers/gles2/rasterizer_gles2.cpp:134.
ERROR: _gl_debug_print: GL ERROR: Source: OpenGL        Type: Error     ID: 2   Severity: High  Message: GL_INVALID_OPERATION in glTexImage2D(bad target for texture)
   At: drivers/gles2/rasterizer_gles2.cpp:134.
ERROR: _gl_debug_print: GL ERROR: Source: OpenGL        Type: Error     ID: 2   Severity: High  Message: GL_INVALID_OPERATION in glTexImage2D(bad target for texture)
   At: drivers/gles2/rasterizer_gles2.cpp:134.
ERROR: _gl_debug_print: GL ERROR: Source: OpenGL        Type: Error     ID: 2   Severity: High  Message: GL_INVALID_OPERATION in glTexImage2D(bad target for texture)
   At: drivers/gles2/rasterizer_gles2.cpp:134.
ERROR: _gl_debug_print: GL ERROR: Source: OpenGL        Type: Error     ID: 2   Severity: High  Message: GL_INVALID_OPERATION in glTexImage2D(bad target for texture)
   At: drivers/gles2/rasterizer_gles2.cpp:134.
ERROR: _gl_debug_print: GL ERROR: Source: OpenGL        Type: Error     ID: 2   Severity: High  Message: GL_INVALID_OPERATION in glTexImage2D(bad target for texture)
   At: drivers/gles2/rasterizer_gles2.cpp:134.
ERROR: _gl_debug_print: GL ERROR: Source: OpenGL        Type: Error     ID: 2   Severity: High  Message: GL_INVALID_OPERATION in glTexImage2D(bad target for texture)
   At: drivers/gles2/rasterizer_gles2.cpp:134.
ERROR: _gl_debug_print: GL ERROR: Source: OpenGL        Type: Error     ID: 2   Severity: High  Message: GL_INVALID_OPERATION in glTexImage2D(bad target for texture)
   At: drivers/gles2/rasterizer_gles2.cpp:134.
ERROR: _gl_debug_print: GL ERROR: Source: OpenGL        Type: Error     ID: 2   Severity: High  Message: GL_INVALID_OPERATION in glTexImage2D(bad target for texture)
   At: drivers/gles2/rasterizer_gles2.cpp:134.
ERROR: initialize: Directional shadow framebuffer status invalid
   At: drivers/gles2/rasterizer_scene_gles2.cpp:3355.
Audio buffer frames: 512 calculated latency: 11ms
error: lima_blit not implemented

error: lima_blit not implemented

error: lima_blit not implemented

error: lima_blit not implemented

error: lima_blit not implemented

error: lima_blit not implemented

error: lima_blit not implemented

error: lima_blit not implemented

CORE API HASH: 0
EDITOR API HASH: 0
ERROR: _gl_debug_print: GL ERROR: Source: OpenGL        Type: Error     ID: 2   Severity: High  Message: GL_INVALID_FRAMEBUFFER_OPERATION in glClear(incomplete framebuffer)
   At: drivers/gles2/rasterizer_gles2.cpp:134.
WARNING: _render_target_allocate: Could not create framebuffer!!
   At: drivers/gles2/rasterizer_storage_gles2.cpp:4605.
ERROR: _gl_debug_print: GL ERROR: Source: OpenGL        Type: Error     ID: 2   Severity: High  Message: GL_INVALID_FRAMEBUFFER_OPERATION in glClear(incomplete framebuffer)
   At: drivers/gles2/rasterizer_gles2.cpp:134.
Loading resource: res://Stage.tscn
Loading resource: res://TileSet.tres
Loading resource: res://tiles_demo.png
Loading resource: res://coin/Coin.tscn
Loading resource: res://coin/coin.gdc
Loading resource: res://player/player.gdc
Loading resource: res://player/Bullet.tscn
Loading resource: res://player/bullet.gdc
Loading resource: res://player/bullet.png
Loading resource: res://coin/coin.png
Loading resource: res://audio/sound_coin.wav
Loading resource: res://platform/MovingPlatform.tscn
Loading resource: res://platform/moving_platform.gdc
Loading resource: res://platform/moving_platform.png
Loading resource: res://platform/OneWayPlatform.tscn
Loading resource: res://platform/one_way_platform.png
Loading resource: res://player/Player.tscn
Loading resource: res://player/robot_demo.png
Loading resource: res://audio/sound_jump.wav
Loading resource: res://audio/sound_shoot.wav
Loading resource: res://player/osb_left.png
Loading resource: res://player/osb_right.png
Loading resource: res://player/osb_jump.png
Loading resource: res://player/osb_fire.png
Loading resource: res://enemy/Enemy.tscn
Loading resource: res://enemy/enemy.gdc
Loading resource: res://enemy/enemy.png
Loading resource: res://audio/sound_hit.wav
Loading resource: res://audio/sound_explode.wav
Loading resource: res://background/ParallaxBg.tscn
Loading resource: res://background/scroll_bg_sky.png
Loading resource: res://background/scroll_bg_cloud_1.png
Loading resource: res://background/scroll_bg_cloud_2.png
Loading resource: res://background/scroll_bg_cloud_3.png
Loading resource: res://background/scroll_bg_fg_2.png
Loading resource: res://background/scroll_bg_fg_1.png
Loading resource: res://audio/music.ogg
ALSA lib pcm.c:8306:(snd_pcm_recover) underrun occurred
```
