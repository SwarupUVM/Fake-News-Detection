# Fake-News-Detection
The MVAE model is based on the MVAE Fake news detection model
SpotFake model is based on the SpotFake Fake news detection model
No	Model	Accuracy	         Fake News	              Real News
			              Precision	Recall	F1-Score	Precision	Recall	F1-Score
1	mBert−CLIP	0.744	0.694	0.555	0.617	0.764	0.855	0.807
2	mBERT−ResNet101	0.773	0.70	0.68	0.69	0.82	0.83	0.82
3	mBERT−VGG19 ReLU activation	0.762	1.00	0.36	0.529	0.724	1.00	0.840
4	mBERT−VGG19 ELU activation	0.886	0.99	0.697	0.820	0.84	0.99	0.917
5	ALBERT−VGG19	0.868	0.975	0.663	0.789	0.832	0.990	0.904
6	CLIP−CosSim	0.812	0.69	1.00	0.82	1.00	0.74	0.85
7	MMoE−CNN	0.859	0.78	0.86	0.82	0.91	0.86	0.88
