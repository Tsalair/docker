# ДЗ по docker

Необходимо собрать  контейнер smarthome командой

```
docker image build -t smarthome .
```
а затем запустить его командой

```
docker run -it --rm -p 8000:8000 smarthome
```
