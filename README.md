# tsconfig
tsconfig for k8s deploy
build rpm:
fpm -f -s dir --name tsconfig -a noarch -t rpm --version 1.0 -C ./ -p .
