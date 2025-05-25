This project investigates how customer segments respond differently to pricing levels, aiming to support data-driven pricing strategies. A synthetic dataset of 5,000 customers is generated and divided into three segments: New, Returning, and Loyal. Each customer is randomly assigned to one of three price points: Low, Medium, or High.

Conversion behavior is simulated using a predefined sensitivity matrix—where loyal customers convert consistently, while new customers show sharp drop-offs at higher prices. The simulation also includes purchase values to evaluate potential revenue impact.

Using pandas, the notebook calculates segment-wise conversion rates and visualizes results using bar charts and heatmaps. Key insights reveal that Loyal customers are less price-sensitive and convert well even at high prices, while New customers require lower prices to engage.

These insights suggest that differentiated pricing could maximize revenue by segment. The analysis is fully implemented in Python using pandas, numpy, seaborn, and matplotlib.