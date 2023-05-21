Migration from DOTween to PrimeTween
---
This repo shows how a reasonably big project [MotionDesignFES](https://github.com/Yusuke57/MotionDesignFES) with dozens of animations was migrated from DOTween to PrimeTween in a few lines of code.

Migrating to PrimeTween gives a significant performance boost, especially on hot code paths because PrimeTween doesn't allocate heap memory and doesn't trigger garbage collection.

#### [PrimeTween documentation](https://github.com/KirillKuzyk/PrimeTween)
#### [Migration guide](https://github.com/KirillKuzyk/PrimeTween#migrating-from-dotween-to-primetween)