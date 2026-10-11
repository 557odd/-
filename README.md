# DeepFaceLab


## Process

1. Extract the 7z file (3000 RTX series
2. After extracting, you’ll find a 9.8gb faceset.Pak

BATCH FILES in Workspace

(#)

1. Convert video to frames
2. Extract faces (f, wf, head) x 512x512
3. Align faces in the data_src folde, add landmarks 
4. Sort faces (histogram)
5. Pack facesets
   5.1. Train model
    6. Train Quick96
    7. Train SAE

8. Workspace

        data_src
        —-\aligned\faceset.pak
        
        data_dst
        
        —-\aligned\faceset.pak
         After running 9. Merge data_dst
        —-\merged