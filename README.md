# Google-Play-Store
Overview of the Dataset

This dataset is sourced from the "Google Play Store Apps and Reviews" dataset, which contains data on more than 10,000 apps available on Google Play. It aims to provide a comprehensive understanding of the Android app market through various metrics like ratings, reviews, installs, pricing, and app categories. The purpose of this analysis is to uncover trends, identify high-performing categories, and recommend strategies to boost growth and retention.

Dataset Contents:

apps.csv: Contains 13 attributes per app including app name, category, rating, reviews, installs, size, price, content rating, genres, and Android version.

user_reviews.csv: Includes 100 reviews per app, with sentiment, sentiment polarity, and subjectivity.

Data Cleaning Steps (Performed using SQL)

Removed duplicates to maintain data integrity.

Filtered out apps with missing critical values (e.g., no ratings, reviews, or install data).

Cleaned and converted text data (e.g., prices and install numbers) into numeric values.

Standardized Android version information.

Normalized categories and genres for consistency.

Key Insights (with Brief Explanations)

Average number of reviews per app is 128,000
→ Indicates high user engagement. Many users leave feedback, which can influence others' decisions.

Average price is $1.2
→ Most apps are free or low-cost. Pricing strategy is critical in a competitive market.

Average rating is 4.16 out of 5
→ The majority of apps are well-rated, showing general user satisfaction.

Gaming apps lead in number of installs
→ Games are the most popular category even if their average rating is lower. Indicates strong demand regardless of performance.

Highest number of installs occur in Q3
→ Possibly tied to vacation seasons and holidays, leading to more app usage.

Free apps dominate downloads (≈99%)
→ Users prefer free content; monetization may rely on ads or in-app purchases.

Paid apps have higher average ratings (24.23%) than free ones (15%)
→ Users are more satisfied with paid apps, possibly due to better quality or fewer ads.

Finance, Lifestyle, and Medical apps have the highest prices
→ These niches possibly target professional or high-value users.

Most popular Android version for downloads is 2.0.1
→ Compatibility with older versions remains important.

Least used Android version is 1.0
→ Indicates technological obsolescence.

Recommendations

Focus on Free App Strategies: Since nearly all downloads are from free apps, consider freemium or ad-supported models.

Target Gaming Category: Despite lower ratings, gaming apps get the most downloads.

Promote Heavily in Q3: Leverage Q3’s peak download season for marketing.

Improve Quality of Free Apps: Bridging the quality gap between free and paid apps may increase retention.

Consider Paid App Opportunities in Niche Categories: Especially in Finance, Lifestyle, and Medical.

Ensure Backward Compatibility: To capture a broader user base across devices.

Conclusion

The Google Play app ecosystem is dominated by free apps, especially in the gaming sector, which garners the most downloads despite lower average ratings. Q3 stands out as the best time for user acquisition, possibly due to seasonal trends. While free apps lead in installs, paid apps achieve better ratings, suggesting room for monetization with quality offerings. Targeting high-value categories like Finance or Medical, improving app quality, and ensuring compatibility across Android versions are essential strategies for success in this market.

## Live Dashboard

You can view the interactive dashboard here: [Google Play Dashboard on Power BI](https://app.powerbi.com/view?r=eyJrIjoiNTE0ZWIyMjEtYzVmOC00MjRjLTg3NjgtYzc5NjI3MzczNGFmIiwidCI6IjJiYjZlNWJjLWMxMDktNDdmYi05NDMzLWMxYzZmNGZhMzNmZiIsImMiOjl9)
