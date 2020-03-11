# Detecting-Malaria-from-Cell-Images

The Dataset is taken from the official NIH Website: https://ceb.nlm.nih.gov/repositories/malaria-datasets/ .

The aim is to aid microscopists in malaria parasite detection in thin-blood smear images and improve diagnostic accuarcy.

Transfer learning is performed with the Resnet-34 model on the dataset using the fastai library.

An accuracy of ~95% was achieved with the model trained only on 10 epochs. 
There is scope for further improvement with more training. 

Working demonstration - https://detecting-malaria-from-cell-images.onrender.com/
