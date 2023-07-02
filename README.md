# Reference
```
@ARTICLE{10015781,
  author={Lian, Huiqiang and Li, Jiahui and Wu, Hao and Zhao, Yiji and Zhang, Lei and Wang, Xin},
  journal={IEEE Transactions on Network and Service Management}, 
  title={Towards Effective Personalized Service QoS Prediction from the Perspective of Multi-Task Learning}, 
  year={2023},
  volume={},
  number={},
  pages={1-1},
  doi={10.1109/TNSM.2023.3236348}
}
```
# Specification
**3Attributes_Context.tsv**: The original version which consists of 11400 records. 
</br>
**small-3t.csv**: The refined and enhanced version really used in our paper.
</br>

UserID|ServiceID|ResponseTime|Throughput|Reliability|UserRegion|UserAS|UserSubnet|UserIP|UserGP|ServiceRegion|ServiceAS|ServiceSubnet|ServiceIP|ServiceGP|...
------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------
3|3958|0.574|11.547|1.00 |United_States|AS17|AS17_128.10.0.0/16|128.10.19.52|40.4249_-86.9162|Australia|AS9328|AS9328_203.89.199.0/24|203.89.199.52|-37.8139_144.9634|3958.wsdl
3|281|0.281|19.419|1.00 |United_States|AS17|AS17_128.10.0.0/16|128.10.19.52|40.4249_-86.9162|Belgium|AS2611|AS2611_193.190.76.0/24|193.190.76.50|51.05_3.7167|281.wsdl
3|2748|0.131|85.167|1.00 |United_States|AS17|AS17_128.10.0.0/16|128.10.19.52|40.4249_-86.9162|Canada|AS3359|AS3359_129.128.0.0/16|129.128.98.86|53.5248_-113.5334|2748.wsdl
3|2790|1.828|7.778|0.00 |United_States|AS17|AS17_128.10.0.0/16|128.10.19.52|40.4249_-86.9162|Canada|AS3359|AS3359_129.128.0.0/16|129.128.98.86|53.5248_-113.5334|2790.wsdl
3|2867|1.987|7.485|0.00 |United_States|AS17|AS17_128.10.0.0/16|128.10.19.52|40.4249_-86.9162|Canada|AS3359|AS3359_129.128.0.0/16|129.128.98.86|53.5248_-113.5334|2867.wsdl
3|3080|0.126|89.325|1.00 |United_States|AS17|AS17_128.10.0.0/16|128.10.19.52|40.4249_-86.9162|Canada|AS3359|AS3359_129.128.0.0/16|129.128.98.86|53.5248_-113.5334|3080.wsdl
3|3087|1.797|7.772|0.00 |United_States|AS17|AS17_128.10.0.0/16|128.10.19.52|40.4249_-86.9162|Canada|AS3359|AS3359_129.128.0.0/16|129.128.98.86|53.5248_-113.5334|3087.wsdl
3|131|0.618|18.985|0.00 |United_States|AS17|AS17_128.10.0.0/16|128.10.19.52|40.4249_-86.9162|France|AS2200|AS2200_147.99.0.0/16|147.99.102.41|43.5278_1.4824|131.wsdl
3|192|0.399|32.198|1.00 |United_States|AS17|AS17_128.10.0.0/16|128.10.19.52|40.4249_-86.9162|Germany|AS680|AS680_134.76.0.0/16|134.76.31.209|51.5333_9.9333|192.wsdl

**WSDL**: For the details of WSDL files,  please refer to: https://github.com/whale-ynu/DNM/blob/main/_wsdl.zip
