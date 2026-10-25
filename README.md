You need to paste 16 lines of the same ID but with different bytes.
Even if you have duplicates, it ignores them.
Also if you don't have all of the sequences, it will just say NONE where it's missing.
If it sees that the padding byte results to the same value from at least 2 sequences, it creates the whole kennung array directly.
