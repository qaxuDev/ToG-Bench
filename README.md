
# ToG-Bench: Task-Oriented Spatio-Temporal Grounding in Egocentric Videos

**Official benchmark for ArXiv**:  
ToG-Bench is the first benchmark for *task-oriented* spatio-temporal video grounding in egocentric videos. Instead of grounding objects based on descriptive language (e.g., “the red cup”), it requires reasoning about *intended actions* (e.g., “grab something to drink”).

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
If you use ToG-Bench in your research, please cite our CVPR 2026 paper:

```bibtex
@inproceedings{xu2026togbench,
  title     = {{ToG-Bench}: Task-Oriented Spatio-Temporal Grounding in Egocentric Videos},
  author    = {Qi'ao Xu, Tianwen Qian, Yuqian Fu, Kailing Li, Yang Jiao, Jiacheng Zhang, Xiaoling Wang and Liang He},
  booktitle = {ArXiv},
  year      = {2025}
}
