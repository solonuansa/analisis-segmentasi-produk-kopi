# Coffee Product Segmentation Analysis

This project applies K-Means Clustering and Principal Component Analysis (PCA) to segment coffee products across various regions, aiming to uncover actionable insights for business strategy and marketing optimization.

## Objectives

- Identify potential market segments for coffee products.
- Analyze sales patterns and consumer preferences by region and product.
- Provide data-driven recommendations for targeted marketing and operational efficiency.

## Methodology

1. **Data Exploration**  
   Initial exploration to understand distributions, outliers, and variable relationships.

2. **Data Preprocessing**  
   - Data cleaning (handling missing values and outliers).
   - Feature standardization to ensure comparability.

3. **Assumption Testing**  
   - Kaiser-Meyer-Olkin (KMO) test for sampling adequacy.
   - Multicollinearity check using Variance Inflation Factor (VIF).

4. **Dimensionality Reduction**  
   - Principal Component Analysis (PCA) to address multicollinearity and reduce dimensionality.

5. **Clustering**  
   - Determination of optimal cluster number using Elbow and Silhouette methods.
   - Implementation of K-Means clustering on PCA-transformed data.

6. **Evaluation & Interpretation**  
   - Analysis of cluster characteristics.
   - Visualization and summary of segmentation results.

## Key Findings

- Three main clusters were identified, each representing distinct business performance profiles:
  - **Cluster 1:** High sales and profit, requiring significant marketing investment.
  - **Cluster 2:** Moderate performance, balanced between revenue and costs.
  - **Cluster 3:** Low sales and profit, indicating potential areas for improvement or strategic adjustment.
- PCA reduced the data to two principal components, explaining over 96% of the variance.

## Report Presentation: HTML and CSS Features

The analysis report is generated as an interactive HTML document using R Markdown, with several advanced features to enhance readability, accessibility, and user experience:

- **Custom CSS Styling:**  
  The report uses a custom `style.css` file to improve the visual appearance. Key enhancements include:
  - Modern typography and responsive layout for readability on all devices.
  - Table formatting with alternating row colors and hover effects for clarity.
  - Color schemes designed for both light and dark backgrounds.
  - **Dark Mode:** Users can switch between light and dark themes for comfortable viewing in different environments.
  - **Star Mode:** A special highlight mode ("star mode") is available to emphasize key findings or important sections, making them stand out visually.
  - Custom button styles, smooth transitions, and visually distinct alerts or notes.

- **HTML Document Options:**  
  - Table of contents (TOC) with floating navigation for easy access to all sections.
  - Code folding, allowing readers to hide or show R code blocks as needed for a cleaner view.
  - Smooth scrolling and animated navigation for seamless movement between sections.
  - Responsive design ensures the report looks good on desktops, tablets, and mobile devices.

- **Custom HTML Header:**  
  Additional HTML elements are included via `function.html` to further customize the header, add branding elements (such as logos or banners), and provide quick links to related resources.

These enhancements ensure the report is visually appealing, easy to navigate, and accessible to a broad audience, while also providing interactive and user-friendly features for exploring complex analyses.

## Project Report

The full analysis report, including interactive visualizations and detailed methodology, is available online: [rpubs.com/solonuansa/segmentasi-produk-kopi](https://rpubs.com/solonuansa/segmentasi-produk-kopi)
