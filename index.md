### Abstract
Voice  conversion  (VC)  is  a  task  that  transforms  the  sourcespeaker’s timbre, accent, and tones in audio into another one’swhile preserving the linguistic content.  It is still a challengingwork, especially in one-shot setting.  Auto-encoder-based VCmethods disentangle the speaker and the content in input speechwithout given the speaker’s identity, so these methods can fur-ther generalize to unseen speakers.  The disentangle capabilityis achieved by vector quantization (VQ), adversarial training, orinstance normalization (IN). However, the imperfect disentan-glement may harm the quality of output speech.  In this work,to further improve audio quality, we fuse skip-connection mod-ules  into  an  auto-encoder-based  VC  system.   We  find  that  toleverage skip-connection, strong information bottleneck is nec-essary.  The VQ-based method, which quantizes the latent vec-tors,  can serve the purpose.   The objective and the subjectiveevaluations  show  that  the  proposed  method  performs  well  inboth audio naturalness and speaker sim
### Demo 1 F2M

| **Source** | **Target** | ** Ours Converted** | ** AdaIN ** | ** AutoVC** |
| :--- | :--- | :--- | :--- | :--- |
| <audio src="all/p237_p251_0/source.wav" controls preload></audio> | <audio src="all/p237_p251_0/target.wav" controls preload></audio> | <audio src="all/p237_p251_0/conversion.wav" controls preload></audio> |<audio src="all/p237_p251_0/adain/converted.wav" controls preload></audio> |<audio src="all/p237_p251_0/autovc/source.wav" controls preload></audio> |
| --- | --- | --- | --- | --- |

### Demo 2 M2F

| **Source** | **Target** | **Converted** |
| :--- | :--- | :--- |
| <audio src="demo/demom2f01/inp.wav" controls preload></audio> | <audio src="demo/demom2f01/inp2.wav" controls preload></audio> | <audio src="demo/demom2f01/convert.wav" controls preload></audio> |
| --- | --- | --- |
| <audio src="demo/demom2f03/inp.wav" controls preload></audio> | <audio src="demo/demom2f03/inp2.wav" controls preload></audio> | <audio src="demo/demom2f03/convert.wav" controls preload></audio> |
| --- | --- | --- |
| <audio src="demo/demom2f04/inp.wav" controls preload></audio> | <audio src="demo/demom2f04/inp2.wav" controls preload></audio> | <audio src="demo/demom2f04/convert.wav" controls preload></audio> |
| --- | --- | --- |

### Demo 3 M2M

| **Source** | **Target** | **Converted** |
| :--- | :--- | :--- |
| <audio src="demo/demom2m01/inp.wav" controls preload></audio> | <audio src="demo/demom2m01/inp2.wav" controls preload></audio> | <audio src="demo/demom2m01/convert.wav" controls preload></audio> |
| --- | --- | --- |
| <audio src="demo/demom2m02/inp.wav" controls preload></audio> | <audio src="demo/demom2m02/inp2.wav" controls preload></audio> | <audio src="demo/demom2m02/convert.wav" controls preload></audio> |
| --- | --- | --- |
| <audio src="demo/demom2m04/inp.wav" controls preload></audio> | <audio src="demo/demom2m04/inp2.wav" controls preload></audio> | <audio src="demo/demom2m04/convert.wav" controls preload></audio> |
| --- | --- | --- |

### Demo 3 F2F

| **Source** | **Target** | **Converted** |
| :--- | :--- | :--- |
| <audio src="demo/demof2f01/inp.wav" controls preload></audio> | <audio src="demo/demof2f01/inp2.wav" controls preload></audio> | <audio src="demo/demof2f01/convert.wav" controls preload></audio> |
| --- | --- | --- |
| <audio src="demo/demof2f02/inp.wav" controls preload></audio> | <audio src="demo/demof2f02/inp2.wav" controls preload></audio> | <audio src="demo/demof2f02/convert.wav" controls preload></audio> |
| --- | --- | --- |
| <audio src="demo/demof2f03/inp.wav" controls preload></audio> | <audio src="demo/demof2f03/inp2.wav" controls preload></audio> | <audio src="demo/demof2f03/convert.wav" controls preload></audio> |
| --- | --- | --- |