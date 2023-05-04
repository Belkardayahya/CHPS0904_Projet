# CHPS0904_Projet
Dans le cadre du projet CHPS904, deux dossiers ont été créés : Generative_inpainting et DeepFillv2_Pytorch. Malgré mes efforts, je n'ai pas pu entraîner les modèles avec les données fournies qui se trouvent dans le dossier /home/blamiroy/LEHIGH-ENGINEERING pour les deux versions.

La version DeepFillv2 est une réimplémentation de DeepFillv2 qui s'inspire de Generative_inpainting. Les détails techniques sont expliqués dans le rapport. Pour tester le code, voici les étapes à suivre :

## Test
`
cd deepfill_v2. 
python test.py --image examples/inpaint/case1.png --mask examples/inpaint/case1_mask.png --out examples/inpaint/case1_out_test.png --checkpoint pretrained/states_tf_places2.pth
`
