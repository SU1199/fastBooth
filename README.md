# fastbooth

Fast dreambooth notebook for dockerised compute platforms like vast.ai, runpod and paperspace grdient.
Heavily {{inspired}} by [ShivamShrirao](https://github.com/ShivamShrirao/diffusers) and [TheLastBen](https://github.com/TheLastBen/fast-stable-diffusion).

---
### How to use?


For vast.ai ->

- Click on edit image and config
- Select an empty templte slot.
- Enter `paperspace/gradient-base:pt112-tf29-jax0317-py39-20221019` in the docker image section.
- Select launch mode as jupyterlab and press select and save.
- I reccomend getting a 25+Gb machine with atleaset 24gb of vrm. My fav. are the a5000 machines.
- After launching the jupyterlab.
- Enter `!wget https://raw.githubusercontent.com/su1199/fastbooth/main/fastbooth.ipynb` in a cell and run it.
- Open the `fastbooth.ipynb` from the file tree and follow the notebook.a
- Add direct inference from .ckpt files.
- Add backbalze/s3 support.
