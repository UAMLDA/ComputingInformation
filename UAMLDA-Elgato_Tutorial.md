# About the UAMLDA Computing Resources 

This tutorial aims at clarifying how to use [Elgato](http://elgato.arizona.edu/) at the [High Performance Computing Center (HPC)](https://it.arizona.edu/service/high-performance-computing) at The University of Arizona. Elgato has 128 Tesla K20X GPU, which makes very useful in large-scale machine learning problems. Students can upload code to Elgato can run TensorFlow applications using Elgato's GPU. This can save a lot of time.


# Contact Information

If you have any questions about the content of this tutorial, here are some people you may find helpful:

* HPC consultants (hpc-consult@list.arizona.edu). This list contains the experts who maintain the Elgato service at UA's HPC center.
* Prof. Ditzler(ditzler@email.arizona.edu). 
* Zhengzhong Liang (zhengzhongliang@email.arizona.edu), who writes this tutorial.

# Login to the Elgato System

## Get Sponsored
Before you can login to the HPC, you need to get sponsored by a faculty. You can talk to Prof. Ditzler to discuss the sponsorship.

## Login via SSH
After you are sponsored, you can login to the HPC server using terminal. For example in Linux, you can press 'alt+ctrl+t' to open a terminal. Then in terminal, type the following commands to login:

'''
ssh username@hpc.arizona.edu
'''

Then you are required to enter the password. You should enter the password corresponding to your NetID. Then the system requires an additional security verification. For me I use Duo Push for IOS. Thus after I select it using terminal, HPC will send a request to my phone. And I should confirm this request on my phone. After this two-factor verfication (password + Duo), I can login to the system.

The final step is to choose which platform we want to use. There are 3 in total: elgato, ocelote and ICE. Since we want to use elgato, we enter elgato.

## Run TensorFlow Application on Elgato

To run any resource on Elgato, you need to firstly apply for computation resources. Please do not run any application without firstly applying for resources. 

The following script is 'submit.sh'. It includes content about how to apply for computation resource on Elgato:

To be filled

