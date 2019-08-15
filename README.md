# data-agumentation-for-object-detection
Here is a set of commonly used and more systematic data enhancement method
运行'labelpoint.py'文件可以通过在图片中点击想要标注的关键点将其信息存入label.txt文件中
运行'showrec.py'文件可为label.txt文件中的每个点生成一个b_box（以该点为中心）
'txt2xml.py'可将dataaug.py生成的标注信息txt文件转换为VOC数据集中的xml文件
'to_main.py'可将所有数据分为trainval、train、val、test四个数据集，并将数据集中图片的标号存入Main文件夹下相应txt文件中
'voc_annotation.py'将读取xml文件和Main文件夹中的不同的数据集及其数据信息并将其输出为可输入网络训练程序的txt文件
