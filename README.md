
# ToG-Bench: Task-Oriented Spatio-Temporal Grounding in Egocentric Videos

**Official benchmark for T-STVG**:  
ToG-Bench is the first benchmark for *task-oriented* spatio-temporal video grounding in egocentric videos. Instead of grounding objects based on descriptive language (e.g., "the red cup"), it requires reasoning about *intended actions* (e.g., "Use the marker to write on the whiteboard", "Turn on what's near the refrigerator to imporve the air quality").

## 🌟 Key Features
- **Task-oriented grounding**: Localize objects by agent intent, not appearance.
- **Explicit–Implicit Dual Grounding**: Targets may be stated or require contextual inference.
- **One-to-Many Grounding**: Single instructions can involve multiple task-relevant objects.
- **2,704 human-refined instructions** across 100 egocentric clips from ScanNet.
- **Task-aware evaluation metrics** for multi-object and implicit grounding.

## 📊 Benchmark Results
We evaluate 7 state-of-the-art MLLMs and reveal significant gaps in handling implicit and multi-object task grounding, highlighting the challenge of aligning perception with embodied interaction.

## 📥 Data & Code
- [ ] Annotation data (coming soon)
- [ ] Evaluation scripts (coming soon)
- [ ] Leaderboard (coming soon)

## 📄 Citation
If you find our paper and code useful in your research, please consider giving a citation:

```bibtex
@article{xu2026togbench,
  title     = {ToG-Bench: Task-Oriented Spatio-Temporal Grounding in Egocentric Videos},
  author    = {Qi'ao Xu, Tianwen Qian, Yuqian Fu, Kailing Li, Yang Jiao, Jiacheng Zhang, Xiaoling Wang and Liang He},
  booktitle = {arXiv preprint arXiv:2512.03666},
  year      = {2025}
}
