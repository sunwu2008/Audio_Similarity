# Audio_Similarity
Detect and log all segments in the full MP3 that match the sample with similarity above a chosen threshold  -


--------------------------------***------------------------------
python Audio_smilarity.py --i s.mp3 --r sample.mp3 --s 10
Loading and normalizing MP3 files...
Searching for segments with similarity > 10.0%...
Analyzing 103670 segments (step=50ms)...
Scanning: 100%|████████████████████████████████████████████████████████████████████████████████████████████████████████| 103671/103671 [00:02<00:00, 37418.68it/s]

✅ 20 matches found.
📄 Log written to match_log.txt
Match: 21:42.750 → 21:47.727 | Similarity: 0.19
Match: 21:53.400 → 21:58.377 | Similarity: 0.12
Match: 21:54.650 → 21:59.627 | Similarity: 0.20
Match: 21:54.850 → 21:59.827 | Similarity: 0.11
Match: 21:55.200 → 22:00.177 | Similarity: 0.12
Match: 21:56.100 → 22:01.077 | Similarity: 0.11
Match: 31:05.750 → 31:10.727 | Similarity: 0.11
Match: 31:07.000 → 31:11.977 | Similarity: 0.29
Match: 31:08.800 → 31:13.777 | Similarity: 0.17
Match: 31:13.750 → 31:18.727 | Similarity: 0.10
Match: 31:15.000 → 31:19.977 | Similarity: 0.33
Match: 31:16.800 → 31:21.777 | Similarity: 0.17
Match: 42:36.500 → 42:41.477 | Similarity: 0.12
Match: 42:39.900 → 42:44.877 | Similarity: 0.10
Match: 42:40.100 → 42:45.077 | Similarity: 0.17
Match: 42:41.350 → 42:46.327 | Similarity: 0.12
Match: 53:20.050 → 53:25.027 | Similarity: 0.15
Match: 64:53.600 → 64:58.577 | Similarity: 0.12
Match: 65:05.300 → 65:10.277 | Similarity: 0.26
Match: 65:05.500 → 65:10.477 | Similarity: 0.13


