wget https://github.com/docker/compose/releases/download/1.29.2/docker-compose-Linux-x86_64

docker push javierpipa/postgress
docker-compose up --build

/etc/default/grub
GRUB_CMDLINE_LINUX="cdgroup_enable=memory swapaccount=1"