**Type Piano Community Edition is the complete application and is free to download and use.**

Type Piano 0.1.6 corrects the sampled middle-C pitch and refines the native interface for stable, responsive play.

- The Salamander piano-bank importer now follows the SFZ default middle-C pitch center when a region omits it, so the B3, C4, and C-sharp 4 sample zone plays at the intended pitch instead of nearly one semitone high.
- The native interface now uses egui and eframe 0.35 with an audited software-renderer fallback and event-driven redraws, keeping virtual-machine and software-only Windows sessions responsive without continuous repainting.
- Window controls, resizing, status placement, and the related Hannes Software music-product view are aligned while the complete keyboard, MIDI, sampled-piano, and offline experience remains free.
