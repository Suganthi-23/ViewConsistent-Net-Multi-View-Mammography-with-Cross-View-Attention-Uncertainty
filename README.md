# ViewConsistent-Net-Multi-View-Mammography-with-Cross-View-Attention-Uncertainty

I built this project to address a critical limitation in breast cancer detection systems, where most models rely on single-view mammograms and fail to capture consistency between CC and MLO projections, leading to unreliable or conflicting predictions.

To solve this, I designed and developed a multi-view deep learning framework that jointly processes both views and enforces cross-view consistency. I implemented a dual-stream CNN architecture to extract features independently from CC and MLO images, and introduced a cross-view attention mechanism to dynamically align and integrate complementary information between the two views.

To improve reliability and real-world usability, I integrated Bayesian uncertainty estimation using Monte Carlo dropout, enabling the model to produce confidence-aware predictions and identify uncertain cases that require further clinical review. This makes the system not only accurate but also safer and more interpretable for medical decision support.

Compared to traditional single-view and naive multi-view approaches, my system reduces inconsistent predictions and improves robustness by combining spatial alignment with uncertainty-aware inference. I also incorporated explainability techniques such as Grad-CAM to visualize model focus regions, helping bridge the gap between AI predictions and clinical interpretability.

The system is designed with a strong focus on reliability, interpretability, and real-world clinical deployment.
