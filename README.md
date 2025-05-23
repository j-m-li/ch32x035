
# CH32X035G8U6

## Build firmware uploader

```
git clone https://github.com/jnk0le/openocd-wch.git
cd openocd-wch
git submodule init
git submodule update
(cd src/jtag/drivers/libjaylink/; autoreconf -ivf)
autoreconf -ivf
./configure --enable-static --disable-shared  --enable-wlinke --disable-ch347
```


