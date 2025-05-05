# milkv-golang-setup

<code>
docker run --privileged -itd --name duodocker -v "$(pwd)":/home/work milkvtech/milkv-duo:latest /bin/bash
</code>

<code>
docker exec -it duodocker /bin/bash -c "cd /home/work && cat /etc/issue && ./build.sh [board]"
</code>

<code>
milkv-duo-sd
milkv-duo-spinand
milkv-duo-spinor
milkv-duo256m-sd
milkv-duo256m-spinand
milkv-duo256m-spinor
milkv-duos-emmc
milkv-duos-sd
</code>
