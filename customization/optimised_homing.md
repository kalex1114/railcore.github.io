Standard macros are slow for several reasons

i. probe speed and height are pretty large when doing repeated levelling
1. calling home x/y/z , bed and mesh probing all start with a Z up <do thing> and Z down to avoid crashes

creating "sub-macros" that are the heart of common procedures (such as home Y) means you can hugely optimise your macros by speeding up certain probes and not repeatedly going up and down for no reason.
