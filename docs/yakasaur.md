# Yakasaur

<figure markdown>
  ![Yakasaur 3D Design in OnShape](images/yakasaur-3d.png){ width="300"}
  <figcaption>Yakasaur</figcaption>
</figure>

## Electronics
Current plan is to use ESP-32 as lizard brain and RPi as neocortex
## Mechanics

## Software

Sample python function 

``` py
def sample_function()
    return None
```
Another sample with line highlight taken from here - [mingpt](https://github.com/karpathy/minGPT/blob/master/mingpt/model.py)

``` py title="mingpt" linenums="1" hl_lines="6 7 8"
class GPT(nn.Module):
    """ GPT Language Model """

    @staticmethod
    def get_default_config():
        C = CN()
        # either model_type or (n_layer, n_head, n_embd) must be given in the config
        C.model_type = 'gpt'
        C.n_layer = None
        C.n_head = None
        C.n_embd =  None
        # these options must be filled in externally
        C.vocab_size = None
        C.block_size = None
        # dropout hyperparameters
        C.embd_pdrop = 0.1
        C.resid_pdrop = 0.1
        C.attn_pdrop = 0.1
        return C
```