# CHPS0904_Projet
Le projet CHPS904 comprend deux dossiers : Generative_inpainting et DeepFillv2_Pytorch.
Pour les deux versions j'ai pas réussi d'entrainer le modele sur les données que vous nous a fourni qui sont dans /home/blamiroy/LEHIGH-ENGINEERING.

La version deepfill_v2 est une réimplémentation de deepfillv2 en s'inspirant de generative_inpainting aussi.

L'approche technique est expliqué dans le Rapport.

## Test
python test.py --image examples/inpaint/case1.png --mask examples/inpaint/case1_mask.png --out examples/inpaint/case1_out_test.png --checkpoint pretrained/states_tf_places2.pth
