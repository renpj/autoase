# autoase 自动提交作业

* 只需要提供结构
    * 命令格式：autoase structure [options]
* 自动生成 ase 的 setup.py 文件
* 检查 setup.py 可以生成 INCAR，KPOINTS，POTCAR，POSCAR，以及qsub.job
    * 没有必要生成 VASP 的相关文件，直接生成 ase 文件，就可以提交任务
    * 生成 VASP 文件作为一个选项
* 使用 python 的 template，参考 catmap
    * ase setup 模板
    * vasp 模板
    * qsub 模板
* drag-and-drop 方式提交作业
* 批量作业
* ase gui 弹出，检查结构和固定原子
