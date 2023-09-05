# pytorch-transformer
Attention is all you need implementation


Training Log : 

Max length of source sentence: 309
Max length of target sentence: 274
Processing Epoch 00: 100%|██████████| 1819/1819 [08:38<00:00,  3.51it/s, loss=6.120]
--------------------------------------------------------------------------------
    SOURCE: 'I am going, good-bye!' said Anna, and giving her son a kiss she went up to Karenin and held out her hand to him. 'You were very kind to come.'
    TARGET: — Io vado, addio — disse Anna e, baciato il figlio, si avvicinò ad Aleksej Aleksandrovic, dandogli la mano.
 PREDICTED: — Sì , — disse , — disse Levin , e la sua moglie , e la sua sua moglie , e la sua sua sua moglie , e la sua sua sua sua sua sua sua sua sua sua sua moglie .
--------------------------------------------------------------------------------
    SOURCE: The blaze there has thawed all the snow from your cloak; by the same token, it has streamed on to my floor, and made it like a trampled street.
    TARGET: La fiamma del focolare ha liquefatto la neve che era sul mantello e l'acqua scorre per terra.
 PREDICTED: E non si , e , e , e , e , e a un ’ altro di .
--------------------------------------------------------------------------------
/usr/local/lib/python3.10/dist-packages/torchmetrics/utilities/prints.py:62: FutureWarning: Importing `CharErrorRate` from `torchmetrics` was deprecated and will be removed in 2.0. Import `CharErrorRate` from `torchmetrics.text` instead.
  _future_warning(
/usr/local/lib/python3.10/dist-packages/torchmetrics/utilities/prints.py:62: FutureWarning: Importing `WordErrorRate` from `torchmetrics` was deprecated and will be removed in 2.0. Import `WordErrorRate` from `torchmetrics.text` instead.
  _future_warning(
/usr/local/lib/python3.10/dist-packages/torchmetrics/utilities/prints.py:62: FutureWarning: Importing `BLEUScore` from `torchmetrics` was deprecated and will be removed in 2.0. Import `BLEUScore` from `torchmetrics.text` instead.
  _future_warning(
Processing Epoch 01: 100%|██████████| 1819/1819 [08:34<00:00,  3.53it/s, loss=5.791]
--------------------------------------------------------------------------------
    SOURCE: She was a great reader, and studied a deal; and the "bairns" had taken after her.
    TARGET: La padrona era diversa; leggeva e scriveva volentieri e i figliuoli avevano preso da lei.
 PREDICTED: Era un po ’ di un ’ altra , e il signor Rochester , e il signor Rochester .
--------------------------------------------------------------------------------
    SOURCE: As he turned aside his face a minute, I saw a tear slide from under the sealed eyelid, and trickle down the manly cheek.
    TARGET: Si volse un istante e gli vidi una lagrima brillare fra le palpebre chiuse e scendergli lungo la guancia.
 PREDICTED: Quando era un ’ espressione di un ’ altra , mi aveva detto , e la porta di un ’ altra , e la porta , e la porta di un ’ altra , e la porta .
--------------------------------------------------------------------------------
Processing Epoch 02: 100%|██████████| 1819/1819 [08:34<00:00,  3.53it/s, loss=5.481]
--------------------------------------------------------------------------------
    SOURCE: The trained insight of a Society man enabled Vronsky with a single glance to decide that she belonged to the best Society.
    TARGET: Con l’intuito abituale dell’uomo di mondo, Vronskij ne rilevò l’appartenenza al gran mondo.
 PREDICTED: La sua vita era un ’ espressione di Vronskij , che era un ’ espressione di Vronskij , che egli aveva fatto la questione di cui era stato la vita .
--------------------------------------------------------------------------------
    SOURCE: Meanwhile Mary Nikolavna had come back.
    TARGET: Nel frattempo era tornata Mar’ja Nikolaevna.
 PREDICTED: il dottore .
--------------------------------------------------------------------------------
Processing Epoch 03: 100%|██████████| 1819/1819 [08:35<00:00,  3.53it/s, loss=4.728]
--------------------------------------------------------------------------------
    SOURCE: 'I hate him: and I cannot forgive myself.'
    TARGET: — Lo odio, e non riesco a perdonarmelo.
 PREDICTED: — Io non posso , ma io non posso .
--------------------------------------------------------------------------------
    SOURCE: He noticed that Betsy's delight cooled down when she learnt that Anna had not yet been divorced.
    TARGET: Vronskij notò che l’entusiasmo di Betsy diminuì quando seppe che il divorzio non c’era ancora.
 PREDICTED: Egli si sentiva che il fratello era entrato in cui Anna non aveva mai detto che Anna non era stato accaduto .
--------------------------------------------------------------------------------
Processing Epoch 04: 100%|██████████| 1819/1819 [08:34<00:00,  3.54it/s, loss=4.591]
--------------------------------------------------------------------------------
    SOURCE: It was his valet, who had come for the gloves his master had forgotten.
    TARGET: Era il cameriere che veniva a prendere i guanti dimenticati.
 PREDICTED: Era il cameriere che aveva fatto il cappello di il cappello .
--------------------------------------------------------------------------------
    SOURCE: But Levin could not sit still.
    TARGET: Levin non poteva stare seduto.
 PREDICTED: Ma Levin non poteva .
--------------------------------------------------------------------------------
Processing Epoch 05:  82%|████████▏ | 1483/1819 [07:00<01:35,  3.54it/s, loss=4.579]


