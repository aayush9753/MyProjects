access the chekpoint and download via ...  
https://drive.google.com/file/d/1kjgZX_tGu9MGeO24thhv2PbS6fAY90Ie/view?usp=sharing

checkpoint = {
                 'epoch': epoch + 1,
                    'valid_loss_min': valid_loss,
                    'state_dict': model.state_dict(),
                    'optimizer': optimizer.state_dict(),
                    'scheduler' : scheduler.state_dict()
                }
