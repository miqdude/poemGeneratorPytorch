# Poem Generator In PyTorch

A Seq2seq poem generator written in Python using Pytorch. Code based on chapter 8 of Natural Language Processing in Pytorch. The code originaly used for Neural Machine Translation but I fed the model using poem data and makes it to generate the next sentence of the poem.

# Example outputs

-----------------------------------------------------------------------------------------------------
SOURCE : i a gentle knight was <UNK> on the plaine , <UNK> <UNK> in mightie <UNK> and silver <UNK> , wherein old <UNK> of deepe wounds did remaine , the cruell markes of many a bloudy <UNK> yet <UNK> till that time did he never <UNK> his angry <UNK> did chide his <UNK> <UNK> , as much <UNK> to the <UNK> to yield full jolly knight he seemd , and faire did sitt , as one for <UNK> giusts and fierce <UNK> fitt .

SAMPLED : your the i my land with great our dead , to and which eyes , his own , , and ever first did to glorious dead , , to and by to he unto like , the on her face , light sea , dead with of and her the , all was her hand to is he , dead . . to her the lose , and when her hand into glorious ? , with . am . he , . and to like , the 

TRUTH : ii but on his brest a <UNK> <UNK> he bore , the deare remembrance of his dying lord , for whose sweete sake that glorious badge he wore , and dead as living ever him <UNK> d upon his shield the like was also <UNK> d , for <UNK> hope , which in his helpe he had right <UNK> true he was in <UNK> and word , but of his <UNK> did seeme too <UNK> sad yet nothing did he dread , but ever was <UNK> .

------------------------------------------------------------------------------------------------------
SOURCE : and ye high heavens , the temple of the gods , in which a thousand <UNK> flaming bright doe <UNK> , that to us wretched earthly clods , in dreadful darknesse lend desired light and all ye powers which in the same <UNK> , more then we men can fayne , poure out your blessing on us <UNK> , and happy influence upon us raine , that we may raise a large posterity , which from the earth , which they may long <UNK> , with lasting <UNK> , up to your <UNK> <UNK> may mount , and for the <UNK> of theyr glorious merit may heavenly <UNK> there <UNK> , of blessed saints for to increase the count . 

SAMPLED : so they that , , i that is that that of love , that that s i , love and , the , that which may man . , and that can for ? . 

TRUTH : so let us rest , sweet love , in hope of this , and cease till then our tymely joyes to sing , the woods no more us answer , nor our eccho ring . 

# References
1. Code https://github.com/joosthub/PyTorchNLPBook
1. Data https://www.kaggle.com/ultrajack/modern-renaissance-poetry/data