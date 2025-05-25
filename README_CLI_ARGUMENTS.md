# Command Line Arguments for webui-user.bat

The flags below can be added to the `COMMANDLINE_ARGS` variable in `webui-user.bat` to modify how the application starts.

# --add-stop-route
does not do anything ❌ Flag has no effect

# --administrator
Administrator rights ✅ generally safe on high-end

# --all-in-fp16
No description available. ✅ generally safe on high-end

# --all-in-fp32
No description available. ✅ generally safe on high-end

# --allow-code
allow custom script execution from webui ✅ generally safe on high-end

# --always-batch-cond-uncond
does not do anything ❌ Flag has no effect

# --always-cpu
No description available. ✅ generally safe on high-end

# --always-gpu
No description available. ✅ generally safe on high-end

# --always-high-vram
No description available. ✅ generally safe on high-end

# --always-low-vram
No description available. ✅ generally safe on high-end

# --always-no-vram
No description available. ✅ generally safe on high-end

# --always-normal-vram
No description available. ✅ generally safe on high-end

# --always-offload-from-vram
No description available. ✅ generally safe on high-end

# --api
use api=True to launch the API together with the webui (use --nowebui instead for only the API) ✅ extra capability with little cost

# --api-auth
Set authentication for API like "username:password"; or comma-delimit multiple like "u1:p1,u2:p2,u3:p3" ✅ extra capability with little cost

# --api-log
use api-log=True to enable logging of all API requests ✅ extra capability with little cost

# --api-server-stop
enable server stop/restart/kill via api ✅ extra capability with little cost

# --attention-pytorch
No description available. ✅ generally safe on high-end

# --attention-quad
No description available. ✅ generally safe on high-end

# --attention-split
No description available. ✅ generally safe on high-end

# --autolaunch
open the webui URL in the system's default browser upon launch ✅ generally safe on high-end

# --bsrgan-models-path
Path to directory with BSRGAN model file(s). ✅ useful for organizing files

# --ckpt
path to checkpoint of stable diffusion model; if specified, this checkpoint will be added to the list of checkpoints and loaded ✅ useful for organizing files

# --ckpt-dir
Path to directory with stable diffusion checkpoints ✅ useful for organizing files

# --clip-in-fp16
No description available. ✅ generally safe on high-end

# --clip-in-fp32
No description available. ✅ generally safe on high-end

# --clip-in-fp8-e4m3fn
No description available. ✅ generally safe on high-end

# --clip-in-fp8-e5m2
No description available. ✅ generally safe on high-end

# --clip-models-path
Path to directory with CLIP model file(s), for Interrogate options. ✅ useful for organizing files

# --codeformer-models-path
Path to directory with codeformer model file(s). ✅ useful for organizing files

# --config
path to config which constructs model ✅ useful for organizing files

# --controlnet-dir
Path to directory with ControlNet models ✅ useful for organizing files

# --controlnet-preprocessor-models-dir
Path to directory with annotator model directories ✅ useful for organizing files

# --cors-allow-origins
Allowed CORS origin(s) in the form of a comma-separated list (no spaces) ✅ generally safe on high-end

# --cors-allow-origins-regex
Allowed CORS origin(s) in the form of a single regular expression ✅ generally safe on high-end

# --cuda-malloc
No description available. ✅ generally safe on high-end

# --cuda-stream
No description available. ✅ generally safe on high-end

# --dat-models-path
Path to directory with DAT model file(s). ✅ useful for organizing files

# --data-dir
base path where all user data is stored ✅ useful for organizing files

# --deepdanbooru
does not do anything ❌ Flag has no effect

# --device-id
Select the default CUDA device to use (export CUDA_VISIBLE_DEVICES=0,1,etc might be needed before) ✅ extra capability with little cost

# --directml
No description available. ✅ generally safe on high-end

# --disable-all-extensions
prevent all extensions from running regardless of any other settings ❌ disabling checks not needed on high-end

# --disable-attention-upcast
No description available. ❌ disabling checks not needed on high-end

# --disable-console-progressbars
do not output progressbars to console ❌ disabling checks not needed on high-end

# --disable-extra-extensions
prevent all extensions except built-in from running regardless of any other settings ❌ disabling checks not needed on high-end

# --disable-gpu-warning
No description available. ❌ disabling checks not needed on high-end

# --disable-ipex-hijack
No description available. ❌ disabling checks not needed on high-end

# --disable-model-loading-ram-optimization
disable an optimization that reduces RAM use when loading a model ❌ disabling checks not needed on high-end

# --disable-nan-check
do not check if produced images/latent spaces have nans; useful for running without a checkpoint in CI ❌ disabling checks not needed on high-end

# --disable-opt-split-attention
prefer no cross-attention layer optimization for automatic choice of optimization ❌ disabling checks not needed on high-end

# --disable-safe-unpickle
disable checking pytorch models for malicious code ❌ disabling checks not needed on high-end

# --disable-tls-verify
When passed, enables the use of self-signed certificates. ❌ disabling checks not needed on high-end

# --disable-xformers
No description available. ❌ disabling checks not needed on high-end

# --do-not-download-clip
do not download CLIP model even if it's not included in the checkpoint ✅ generally safe on high-end

# --dump-sysinfo
launch.py argument: dump limited sysinfo file (without information about extensions, options) to disk and quit ✅ generally safe on high-end

# --embeddings-dir
embeddings directory for textual inversion (default: embeddings) ✅ generally safe on high-end

# --enable-console-prompts
does not do anything ❌ Flag has no effect

# --enable-insecure-extension-access
enable extensions tab regardless of other options ✅ extra capability with little cost

# --esrgan-models-path
Path to directory with ESRGAN model file(s). ✅ useful for organizing files

# --filenames-max-length
maximal length of filenames of saved images. If you override it, it can conflict with your file system ✅ generally safe on high-end

# --force-enable-xformers
enable xformers for cross attention layers regardless of whether the checking code thinks you can run it; do not make bug reports if this fails to work ✅ extra capability with little cost

# --force-upcast-attention
No description available. ✅ generally safe on high-end

# --forge-ref-a1111-home
Look for models in an existing A1111 checkout's path ✅ useful for organizing files

# --freeze-settings
disable editing of all settings globally ✅ generally safe on high-end

# --freeze-settings-in-sections
disable editing settings in specific sections of the settings page by specifying a comma-delimited list such like "saving-images,upscaling". The list of setting names can be found in the modules/shared_options.py file ✅ generally safe on high-end

# --freeze-specific-settings
disable editing of individual settings by specifying a comma-delimited list like "samples_save,samples_format". The list of setting names can be found in the config.json file ✅ generally safe on high-end

# --gfpgan-dir
GFPGAN directory ✅ generally safe on high-end

# --gfpgan-model
GFPGAN model file name ✅ generally safe on high-end

# --gfpgan-models-path
Path to directory with GFPGAN model file(s). ✅ useful for organizing files

# --gpu-device-id
No description available. ✅ generally safe on high-end

# --gradio-allowed-path
add path to gradio's allowed_paths, make it possible to serve files from it ✅ useful for organizing files

# --gradio-auth
set gradio authentication like "username:password"; or comma-delimit multiple like "u1:p1,u2:p2,u3:p3" ✅ extra capability with little cost

# --gradio-auth-path
set gradio authentication file path ex. "/path/to/auth/file" same auth format as --gradio-auth ✅ useful for organizing files

# --gradio-debug
launch gradio with --debug option ✅ generally safe on high-end

# --gradio-img2img-tool
does not do anything ❌ Flag has no effect

# --gradio-inpaint-tool
does not do anything ❌ Flag has no effect

# --gradio-queue
does not do anything ❌ Flag has no effect

# --hide-ui-dir-config
hide directory configuration from webui ✅ generally safe on high-end

# --hypernetwork-dir
hypernetwork directory ✅ generally safe on high-end

# --listen
launch gradio with 0.0.0.0 as server name, allowing to respond to network requests ✅ generally safe on high-end

# --localizations-dir
localizations directory ✅ generally safe on high-end

# --log-startup
launch.py argument: print a detailed log of what's happening at startup ✅ generally safe on high-end

# --loglevel
log level; one of: CRITICAL, ERROR, WARNING, INFO, DEBUG ✅ generally safe on high-end

# --lowram
load stable diffusion checkpoint weights to VRAM instead of RAM ❌ memory-saving options unnecessary

# --lowvram
enable stable diffusion model optimizations for sacrificing a lot of speed for very low VRM usage ❌ RTX 4090 has ample VRAM

# --max-batch-count
does not do anything ❌ Flag has no effect

# --medvram
enable stable diffusion model optimizations for sacrificing a little speed for low VRM usage ❌ RTX 4090 has ample VRAM

# --medvram-sdxl
enable --medvram optimization just for SDXL models ❌ memory-saving options unnecessary

# --models-dir
base path where models are stored; overrides --data-dir ✅ useful for organizing files

# --ngrok
ngrok authtoken, alternative to gradio --share ✅ generally safe on high-end

# --ngrok-options
The options to pass to ngrok in JSON format, e.g.: '{"authtoken_from_env":true, "basic_auth":"user:password", "oauth_provider":"google", "oauth_allow_emails":"user@asdf.com"}' ✅ extra capability with little cost

# --ngrok-region
does not do anything. ❌ Flag has no effect

# --no-download-sd-model
don't download SD1.5 model even if no model is found in --ckpt-dir ✅ generally safe on high-end

# --no-gradio-queue
Disables gradio queue; causes the webpage to use http requests instead of websockets; was the default in earlier versions ✅ extra capability with little cost

# --no-half
do not switch the model to 16-bit floats ✅ generally safe on high-end

# --no-half-vae
do not switch the VAE model to 16-bit floats ✅ generally safe on high-end

# --no-hashing
disable sha256 hashing of checkpoints to help loading performance ✅ generally safe on high-end

# --no-progressbar-hiding
do not hide progressbar in gradio UI (we hide it because it slows down ML if you have hardware acceleration in browser) ✅ extra capability with little cost

# --no-prompt-history
disable read prompt from last generation feature; settings this argument will not create '--data_path/params.txt' file ✅ useful for organizing files

# --nowebui
use api=True to launch the API instead of the webui ✅ extra capability with little cost

# --opt-channelslast
change memory type for stable diffusion to channels last ✅ generally safe on high-end

# --opt-sdp-attention
prefer scaled dot product cross-attention layer optimization for automatic choice of optimization; requires PyTorch 2.* ✅ generally safe on high-end

# --opt-sdp-no-mem-attention
prefer scaled dot product cross-attention layer optimization without memory efficient attention for automatic choice of optimization, makes image generation deterministic; requires PyTorch 2.* ✅ generally safe on high-end

# --opt-split-attention
prefer Doggettx's cross-attention layer optimization for automatic choice of optimization ✅ generally safe on high-end

# --opt-split-attention-invokeai
prefer InvokeAI's cross-attention layer optimization for automatic choice of optimization ✅ generally safe on high-end

# --opt-split-attention-v1
prefer older version of split attention optimization for automatic choice of optimization ✅ generally safe on high-end

# --opt-sub-quad-attention
prefer memory efficient sub-quadratic cross-attention layer optimization for automatic choice of optimization ✅ generally safe on high-end

# --pin-shared-memory
No description available. ✅ generally safe on high-end

# --port
launch gradio with given server port, you need root/admin rights for ports < 1024, defaults to 7860 if available ✅ generally safe on high-end

# --precision
evaluate at this precision ✅ generally safe on high-end

# --pytorch-deterministic
No description available. ✅ generally safe on high-end

# --realesrgan-models-path
Path to directory with RealESRGAN model file(s). ✅ useful for organizing files

# --reinstall-torch
launch.py argument: install the appropriate version of torch even if you have some version already installed ✅ generally safe on high-end

# --reinstall-xformers
launch.py argument: install the appropriate version of xformers even if you have some version already installed ✅ generally safe on high-end

# --server-name
Sets hostname of server ✅ generally safe on high-end

# --share
use share=True for gradio and make the UI accessible through their site ✅ extra capability with little cost

# --show-negative-prompt
does not do anything ❌ Flag has no effect

# --skip-google-blockly
launch.py argument: do not initialize google blockly modules ❌ disabling checks not needed on high-end

# --skip-install
launch.py argument: skip installation of packages ❌ disabling checks not needed on high-end

# --skip-load-model-at-start
if load a model at web start, only take effect when --nowebui ❌ disabling checks not needed on high-end

# --skip-prepare-environment
launch.py argument: skip all environment preparation ❌ disabling checks not needed on high-end

# --skip-python-version-check
launch.py argument: do not check python version ❌ disabling checks not needed on high-end

# --skip-torch-cuda-test
launch.py argument: do not check if CUDA is able to work properly ❌ disabling checks not needed on high-end

# --skip-version-check
Do not check versions of torch and xformers ❌ disabling checks not needed on high-end

# --styles-file
path or wildcard path of styles files, allow multiple entries. ✅ useful for organizing files

# --sub-quad-chunk-threshold
the percentage of VRAM threshold for the sub-quadratic cross-attention layer optimization to use chunking ✅ extra capability with little cost

# --sub-quad-kv-chunk-size
kv chunk size for the sub-quadratic cross-attention layer optimization to use ✅ extra capability with little cost

# --sub-quad-q-chunk-size
query chunk size for the sub-quadratic cross-attention layer optimization to use ✅ extra capability with little cost

# --subpath
customize the subpath for gradio, use with reverse proxy ✅ useful for organizing files

# --test-server
launch.py argument: configure server for testing ✅ generally safe on high-end

# --text-encoder-dir
Path to directory with text encoder models ✅ useful for organizing files

# --textual-inversion-templates-dir
directory with textual inversion templates ✅ generally safe on high-end

# --theme
launches the UI with light or dark theme ✅ generally safe on high-end

# --timeout-keep-alive
set timeout_keep_alive for uvicorn ✅ generally safe on high-end

# --tls-certfile
Partially enables TLS, requires --tls-keyfile to fully function ✅ extra capability with little cost

# --tls-keyfile
Partially enables TLS, requires --tls-certfile to fully function ✅ extra capability with little cost

# --ui-config-file
filename to use for ui configuration ✅ extra capability with little cost

# --ui-debug-mode
Don't load model to quickly launch UI ✅ generally safe on high-end

# --ui-settings-file
filename to use for ui settings ✅ extra capability with little cost

# --unet-in-bf16
No description available. ✅ generally safe on high-end

# --unet-in-fp16
No description available. ✅ generally safe on high-end

# --unet-in-fp8-e4m3fn
No description available. ✅ generally safe on high-end

# --unet-in-fp8-e5m2
No description available. ✅ generally safe on high-end

# --unix-filenames-sanitization
allow any symbols except '/' in filenames. May conflict with your browser and file system ✅ generally safe on high-end

# --unload-gfpgan
does not do anything. ❌ Flag has no effect

# --upcast-sampling
upcast sampling. No effect with --no-half. Usually produces similar results to --no-half with better performance while using less memory. ✅ generally safe on high-end

# --update-all-extensions
launch.py argument: download updates for all extensions when starting the program ✅ generally safe on high-end

# --update-check
launch.py argument: check for updates at startup ✅ generally safe on high-end

# --use-cpu
use CPU as torch device for specified modules ✅ extra capability with little cost

# --use-ipex
use Intel XPU as torch device ✅ extra capability with little cost

# --use-textbox-seed
use textbox for seeds in UI (no up/down, but possible to input long seeds) ✅ extra capability with little cost

# --vae-dir
Path to directory with VAE files ✅ useful for organizing files

# --vae-in-bf16
No description available. ✅ generally safe on high-end

# --vae-in-cpu
No description available. ✅ generally safe on high-end

# --vae-in-fp16
No description available. ✅ generally safe on high-end

# --vae-in-fp32
No description available. ✅ generally safe on high-end

# --vae-path
Checkpoint to use as VAE; setting this argument disables all settings related to VAE ✅ extra capability with little cost

# --xformers
enable xformers for cross attention layers ✅ extra capability with little cost

# --xformers-flash-attention
enable xformers with Flash Attention to improve reproducibility (supported for SD2.x or variant only) ✅ extra capability with little cost
