## Just for me
1. 导出分为全量导出，和仅仅导出博客。参数，onlyblog。默认是True
2. 在原有笔记，因为误操作，图片文本格式遭到了修改。导出的时候，需要简单修改一下

# leanote2md
Export all you Markdown notes in Leanote (a.k.a 蚂蚁笔记) to local Markdown files.

## Prerequisite

- Python 3
- pip3
- git

## Dependencies
Use your pip tool to install the dependencies

- anytree
- requests

You can install these packages by this command

```shell
pip3 install anytree requests --user
```

## Usage
Clone this repo, and run the `exporter.py` script. You can easily do this by running the following command on your terminal

```python
git clone https://github.com/gaunthan/leanote2md.git
cd ./leanote2md
chmod +x exporter.py
./exporter.py
```

If you don't want to save your notes interactively, you need to modify `config.py` and run `exporter.py` with command argument `config.py`

```shell
./exporter.py config.py
```
