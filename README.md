# Project_2020
Project from work.
## transfer learning
hands-on experience with deep learning frameworks (PyTorch, TensorFlow, …) 

[Image Classification-resnet18](https://github.com/isabellechiu/Project_2020/blob/main/wih_Defect_Type.ipynb)

## Tensorflow input pipelines
 create MariaDB
 [Create MariaDB by MySQL](https://github.com/isabellechiu/Project_2020/blob/main/P1%26P3_SMT_isa.ipynb)
 
 view image by SQLite
 [sqlite3.connect](https://github.com/isabellechiu/Project_2020/blob/main/view_img_isa.ipynb)
 
 structure TFRecord+Neural Structured Learning
 [create TFRecords to train TensorFlow models+neural_structured_learning](https://github.com/isabellechiu/Project_2020/blob/main/label_adversarial_isa.ipynb)

 
# Git Skills
## How to Setup Passwordless SSH Login.

[source from](https://linuxize.com/post/how-to-setup-passwordless-ssh-login/)

To set up a passwordless SSH login in Linux :generate a public authentication key and append it to the remote hosts ~/.ssh/authorized_keys file.
* Check for existing SSH key pair.
```bash
ls -al ~/.ssh/id_*.pub
```
* Copy the public key to the server.
```bash
ssh-copy-id remote_username@server_ip_address
```
Once the user is authenticated, the public key will be appended to the remote user authorized_keys file and connection will be closed.


