# Note
学习笔记杂谈

## scratch
### 安装不过去的包换成git版本

`"scratch-audio": "git+https://github.com/LLK/scratch-audio.git",`
`"scratch-blocks": "0.1.0-prerelease.1542296154",`
`"scratch-l10n": "^3.0.20181115134359",`
`"scratch-paint": "0.2.0-prerelease.20181114155723 fail",`
`"scratch-render": "git+https://github.com/LLK/scratch-render.git",`
`"scratch-storage": "^1.2.0",`
`"scratch-svg-renderer": "git+https://github.com/LLK/scratch-svg-renderer.git",`
`"scratch-vm": "^0.2.0-prerelease.20181115103725",`


graph LR
A-->B

sequenceDiagram
A->>B: How are you?
B->>A: Great!

gantt
dateFormat YYYY-MM-DD
section S1
T1: 2014-01-01, 9d
section S2
T2: 2014-01-11, 9d
section S3
T3: 2014-01-02, 9d

```flow
st=>start: 开始
op=>operation: My Operation
cond=>condition: Yes or No?
e=>end
st->op->cond
cond(yes)->e
cond(no)->op
&```