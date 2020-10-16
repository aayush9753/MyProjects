checkpoint = { 'epoch': epoch + 1, 'valid_loss_min': valid_loss, 'state_dict': model.state_dict(), 'optimizer': optimizer.state_dict(), 'scheduler' : scheduler.state_dict() }
