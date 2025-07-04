# Exploring-Causality-and-Explainability-in-Time-Series-Models
This is my Masters's Thesis

### Abstract
Causal inference is a powerful tool that allows us to move beyond surface-level correlations and uncover the true cause-and-effect relationships between variables. Whether we’re working with static (non-time series) datasets or dynamic, time-dependent data, understanding \textit{why} something happens is often more valuable than knowing \textit{what} happens. In non-temporal datasets, causal inference helps identify directional influences between variables, often using statistical asymmetries, intervention models, or graphical structures to distinguish genuine causes from mere associations.

In this thesis, we examine the foundational principles of causal inference and how they apply across both non-time series and time series contexts. We explore a range of methodologies for identifying causal links and estimating their strength, with a focus on tools such as directed acyclic graphs (DAGs), structural equation models, and data-driven learning techniques.

A key part of our study focuses on applying these causal inference methods to time series data, where the order of events plays a crucial role. Time-dependent datasets—such as physiological signals of ECG—introduce new challenges, including temporal lags, feedback loops, and hidden confounders. To address these, we incorporate temporal structure into our causal models to better capture the dynamics at play.

Our future work will include implementing these causal techniques on real-world health data to identify significant events, such as abnormal spikes in physiological activity, and to determine the underlying causes. We also aim to build short-term predictive models to forecast metrics like heart rate, and to develop classification systems based on our causal findings. These insights will support early warnings, diagnostics, and informed decision-making. Ultimately, we plan to build machine learning models—including neural networks and random forests—that are enhanced by causal reasoning, making them both more interpretable and more effective for analyzing both static and time-based data.
