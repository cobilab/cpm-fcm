# cpm+fcm

An efficient encoder for biological sequences using Copy Models (CPMs) and Finite-Context models (FCMs)

### Access ###

It is required to clone the repository and give permitions for running the binaries:
```
git clone https://github.com/cobilab/cpm-fcm.git
cd cpm-fcm/
chmod +x cpm+fcm-enc
chmod +x cpm+fcm-dec
```

### Running ###

For running cpm+fcm encoder:
```
./cpm+fcm-enc cpm+fcm.conf protein-file
```
This will generate protein-file.enc.

For running cpm+fcm decoder:
```
./cpm+fcm-dec protein-file.enc
```

This will generate protein-file.enc.dec.

### Parameters ###

To see the options of the encoder:
```
./cpm+fcm-enc
```

This will output:
```
Usage: cpm+fcm-enc [ -v (verbose) ]
                   [ -buf buf_size (in millions of symbols, def 50) ]
                   [ -o encoded_file ]
                   cfg_file inp_file
```

To see the options of the decoder:
```
./cpm+fcm-dec
```

This will output:
```
Usage: cpm+fcm-dec [ -v (verbose) ]
                   [ -# (5% marks) ]
                   [ -o decoded_file ]
                   inp_file
```

### Citation ###

On using this software/method please cite:

* Pinho, A. J., & Pratas, D. (2024, March). Copy models for protein sequence compression. In 2024 Data Compression Conference (DCC) (pp. 342-351). IEEE.

### Issues ###

For any issue let us know at [issues link](https://github.com/cobilab/cpm-fcm/issues).

### License ###

GPL v3.

For more information:
[http://www.gnu.org/licenses/gpl-3.0.html](http://www.gnu.org/licenses/gpl-3.0.html).
