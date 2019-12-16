# Checkout

* Install Google's [`repo`](https://source.android.com/source/downloading) command
* Checkout repos to `syscase-optee` directory:

```bash
mkdir syscase-optee
cd syscase-optee
repo init -u ssh://git@github.com/syscase/syscase-optee-manifest.git
repo sync
```
