# Sebastian's build of st terminal taken from Luke Smith's st build and reconfigured for my taste.

The [suckless terminal (st)](https://st.suckless.org/) with some additional features:

+ To scroll up and down, press alt+j/k (vim bindings). Or up/down
+ Works with pywal
+ Uses your mono system font.
+ Shift+Mouse wheel will also scroll
+ Alt-u and Alt-d scroll back/forward in history a page at a time.
+ Alt-PageUp and Alt-PageDown will do the same.
+ Zoom in/out with Alt+Shift+k/j or u/d for larger intervals.

The following additional bindings were added before I forked this:

## Guide for install

```
make
sudo make install
```
Depencies to build are `fontconfig`, `libX11` and `libXft`. 
