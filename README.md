# Zhongkui Ma (马中奎)

I'm a **PhD Candidate at The University of Queensland** 🎓, working on the **verification, security and privacy of AI systems**.

Neural network verification and convex approximation are the main themes of my PhD. Alongside them I work with collaborators on model and data control, and on privacy in learning and retrieval. Those are different questions answered with different kinds of evidence, so I keep them apart rather than presenting one method applied three times.

[Website](https://zhongkuima.github.io/) · [Research](https://zhongkuima.github.io/research) · [Publications](https://zhongkuima.github.io/publications) · [Writing](https://zhongkuima.github.io/writing)

---

## Research and shared artifacts

Every work below is coauthored, and the repositories belong to the collaborators and labs I work with rather than to me. Each project page carries the full author list, the publication record and the paper link; the repositories are the originals.

| Line | Work | Code |
|---|---|---|
| **Formal Verification & Robustness** — my PhD | [WraLU](https://zhongkuima.github.io/projects/wralu) · [WraAct](https://zhongkuima.github.io/projects/wraact) · [PdD](https://zhongkuima.github.io/projects/pdd) | [WraLU](https://github.com/Trusted-System-Lab/WraLU) · [WraAct](https://github.com/Trusted-System-Lab/WraAct) · [PdD](https://github.com/Trusted-System-Lab/PdD) |
| **Model & Data Control** — collaborative | [CoreLocker](https://zhongkuima.github.io/projects/corelocker) · [AdaLoc](https://zhongkuima.github.io/projects/adaloc) · [AIM](https://zhongkuima.github.io/projects/aim) · [Catch-Only-One](https://zhongkuima.github.io/projects/catch-only-one) | [CoreLocker](https://github.com/CoreLocker/CoreLocker) · [AdaLoc](https://github.com/MLresearchAI/ADALOC) · [AIM](https://github.com/Trusted-System-Lab/AIM) · no public implementation |
| **Privacy in Learning & Retrieval** — collaborative | [GRAB](https://zhongkuima.github.io/projects/grab) · [GHOST](https://zhongkuima.github.io/projects/ghost) · [SHAQ](https://zhongkuima.github.io/projects/shaq) (preprint) | [GRAB](https://github.com/Trusted-System-Lab/GRAB) · [GHOST](https://github.com/Trusted-System-Lab/GHOST) · [SHAQ](https://github.com/shanefeng123/SHAQ) |

Earlier in the PhD I also wrote [*Verifying Neural Networks by Approximating Convex Hulls*](https://doi.org/10.1007/978-981-99-7584-6_17) (ICFEM'23 Doctoral Symposium) as sole author.

🏆 The workshop version of Catch-Only-One, *Non-Transferable Examples* ([ECCV'26 LifeGenIP Workshop](https://lifegenip.cc/)), received a **Best Paper Award Runner-Up**.

The [complete publication list](https://zhongkuima.github.io/publications) also carries the workshop versions and my undergraduate work.

---

## Reusable tools

These are separate from the paper artifacts above, and they run on their own rather than as stages of one pipeline. Note the name collision: `wraact` is my personal Python library, `WraAct` is the OOPSLA'25 artifact.

| Package | Purpose |
|---|---|
| [wraact](https://github.com/ZhongkuiMa/wraact) | Activation-hull approximation |
| [shapeonnx](https://github.com/ZhongkuiMa/shapeonnx) | ONNX tensor-shape inference |
| [slimonnx](https://github.com/ZhongkuiMa/slimonnx) | ONNX model simplification |
| [torchonnx](https://github.com/ZhongkuiMa/torchonnx) | ONNX-to-PyTorch conversion |
| [torchvnnlib](https://github.com/ZhongkuiMa/torchvnnlib) | VNN-LIB specification conversion |

Installation, supported models and reproduction instructions are in each repository's own documentation.

---

## Tutorial

My [NNV tutorial](https://zhongkuima.github.io/guides) works through verification problems, bounds, relaxations and practical specifications. It is a series of study notes under revision, not a substitute for the assumptions and results of the papers it cites.

---

For a bug or a feature request, please use the relevant repository's tracker rather than opening an issue here. And if one of these tools has been useful to you, a star on its repository tells me more than a message does.
