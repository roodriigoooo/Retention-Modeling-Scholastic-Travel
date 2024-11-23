# Retention-Modeling-Scholastic-Travel

A predictive model for customer retention at Scholastic Travel.

### Derived Insights Summary

The most interpretable version of our model provided several meaningful insights into the drivers of customer retention. Below are the key findings based on the model's coefficients:
- **Is.Non.Annual:** Customers not participating in annual programs were significantly less likely to be retained. This negative coefficient suggests that annual engagement is a strong driver of retention, likely due to increased customer commitment and loyalty associated with yearly programs.
- **SPR._NEW:** New customers were less likely to be retained compared to returning ones. This result highlights the importance of building early loyalty among new customers to improve retention.
- **FPP.to.School.enrollment:** A higher ratio of FPP to total school enrollment was positively associated with retention. This suggests that schools with higher program penetration tend to have better retention outcomes, potentially due to increased familiarity and trust.
- **SingleGradeTripFlag:** Trips with students from a single grade were positively correlated with retention. This indicates that focusing on homogeneous groups might improve customer satisfaction and retention, possibly because of easier group management and better social dynamics.
- **Grade_Range:** A wider range of grades within a trip was associated with lower retention. This could indicate that mixed-grade trips are more challenging to manage, leading to lower satisfaction and reduced repeat participation.
- **Total.School.Enrollment:** Larger school enrollments were associated with slightly higher retention. This may be due to larger schools having more resources and infrastructure to support group travel programs.
- **SchoolSize_S:** Smaller school sizes had a negative impact on retention. Smaller schools might lack the resources or support needed to sustain engagement with travel programs.
- **Poverty.Code:** Higher poverty levels were negatively correlated with retention, which indicates that economic constraints could be a barrier to continued participation in these travel programs.
- **MDR.High.Grade:** A higher maximum grade level was slightly negatively associated with retention. Older students may be less inclined to participate in future trips, perhaps due to changing interests or increased academic responsibilities.
- **Days.After.Last.RPL:** Longer periods after the last RPL (Reservation Payment Link) negatively affected retention. This suggests that maintaining timely and frequent interactions is key to ensuring customer commitment.
- **School.Sponsor:** The presence of a school sponsor was positively correlated with retention, underscoring the role of sponsorship in fostering a supportive environment for travel programs.
- **FPP.to.PAX:** Although small, the positive coefficient suggests that the ratio of FPP to total participants had a marginal effect on improving retention.
- **SPR.Product.Type and Income.Level:** Both features had small positive coefficients, indicating minor but consistent contributions to retention. Product type and income level might not be as significant as other factors but still play a role.
- **SchoolGradeType:** The small negative impact of the grade type suggests that variations in school grade levels have minimal influence on retention, but still provide some insights into the complexity of group compositions.

## License

The Scholastic Travel Case and the original datasets are property of the University of Virginia and the Darden School of Business
(Ovchinnikov, [2018](https://hbsp.harvard.edu/product/UV7579-PDF-ENG)).



