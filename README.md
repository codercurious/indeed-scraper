# Indeed Jobs Scraper
Interested in using this scraper? Get it here: [Indeed Jobs Scraper](https://apify.com/curious_coder/indeed-scraper?fpr=ve081&fp_sid=github_indeed-scraper)
## What does Indeed scraper do?
The "Indeed jobs scraper" actor allows you to extract job listings and associated details from [indeed.com](https://indeed.com) job search website. It provides a simple and efficient way to gather job data for analysis, research, lead generation or other purposes.

The actor utilizes web scraping techniques to navigate through search result pages, extract job listings, and retrieve relevant information such as job titles, companies, locations, salaries, and more. It supports various filters and options to customize the scraping process and retrieve specific job data based on your requirements.

## Why scrape indeed.com?
Here are some use cases for an Indeed jobs scraper:

1. **Job Market Research**: Use an Indeed scraper to collect job postings in a specific industry or location. This data can be analyzed to identify trends, such as job demand, salary ranges, and skill requirements, which can inform business strategies or career decisions.

2. **Competitor Analysis**: Monitor your competitors' job postings on Indeed to gain insights into their hiring strategies and the types of positions they are actively recruiting for. This can help you stay competitive in the job market.

3. **Company Research**: Scraper can be used to gather data on companies posting job listings on Indeed, including information about their industry, location, and hiring patterns. This data can be valuable for business development and partnership opportunities.

4. **Salary Benchmarking**: Collect salary information from job postings to understand the average compensation for specific roles in different regions. This data can be used to benchmark your own salary structure or negotiate better compensation.

5. **Location-Based Insights**: Analyze job postings in different geographical locations to identify areas with high demand for specific skills or industries. This information can guide decisions about where to expand or relocate a business.

6. **Lead Generation**: Scraping job postings for contact information (where available) can be used for lead generation. This is particularly useful for B2B companies looking to connect with potential clients or partners in specific industries or roles.

7. **CRM Enrichment**: If you have a CRM (Customer Relationship Management) system, you can use the scraper to enrich your existing contacts with information about their current job positions, companies, and industries. This helps you maintain up-to-date and relevant customer profiles.

8. **Marketplace Insights**: Analyze job postings to understand the demand for certain skills or certifications in the job market. This information can be valuable for educational institutions and training providers to tailor their programs to meet industry needs.

9. **Career Planning**: Individuals can use an Indeed scraper to track job openings in their desired industry or location. This helps with career planning and staying informed about job opportunities that match their skills and interests.

10. **Content Creation**: Bloggers, journalists, or researchers can use scraped job data to create reports, articles, or blog posts about employment trends, job market changes, or emerging industries.

11. **Consulting Services**: Offer consulting services to businesses based on the insights gained from scraping Indeed data. Help companies optimize their hiring processes, identify market gaps, or make informed decisions about expansion and talent acquisition.

## How to scrape indeed
1. Go to [indeed.com](https://indeed.com) and search for jobs with filters such as job title, company name, and location
2. Copy the URL from the address bar. This is the Search URL you need to pass to the scraper
3. Go to [Indeed scraper](https://apify.com/curious_coder/indeed-scraper?fpr=ve081&fp_sid=github_indeed-scraper) on the Apify platform
4. Click the Try for free button
5. Insert the search URL you copied in step 2
6. Enter number of jobs needed
7. Select a residential proxy of your country
8. Click the Start button
9. When the run has finished, click the Export button
10. View and download your data

## Scraper options

Here is are the available options of this scraper:

![Indeed jobs scraper options: job search url and proxy](https://awesomescreenshot.s3.amazonaws.com/image/1021927/43175364-f49ccdcdc39a3bc68e1c4e0b423bfdf8.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAJSCJQ2NM3XLFPVKA%2F20230926%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230926T133848Z&X-Amz-Expires=28800&X-Amz-SignedHeaders=host&X-Amz-Signature=b61e8135850c1afb79e93f100bf57d5740f11b4dcf58e514808d9ed4cbdbbb24)


## Integrations
You can use [Make](https://www.make.com/en/register?pc=growthhack) to integrate apollo leads to any other SaaS platform by designing your own automation flows.


## Sample output
You can download the dataset extracted by indeed scraper in various formats such as JSON, HTML, CSV, or Excel.

![Indeed job scraper results with company details](https://awesomescreenshot.s3.amazonaws.com/image/1021927/43175663-d800ef3baf568df4df0614cfb7d06481.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAJSCJQ2NM3XLFPVKA%2F20230926%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230926T135126Z&X-Amz-Expires=28800&X-Amz-SignedHeaders=host&X-Amz-Signature=1752a549e803e1657ddc5dd25fadfdace396213fb37c4dfa0105f421afb87eac)

Here is the sample JSON output of this actor:

```json
{
	"company": "Dr Martens",
	"viewJobLink": "/viewjob?jk=3c745bd1945cf2f4&from=vjs&tk=1h6p80n3himgp800&viewtype=embedded&continueUrl=%2Fjobs%3Fq%3Dsales%2Bassociate%2Bpart%2Btime%26vjk%3Db28e7b80d0399215%26l%3DNew%2BYork%252C%2BNY",
	"companyBrandingAttributes": {
		"headerImageUrl": "https://d2q79iu7y748jz.cloudfront.net/s/_headerimage/1960x400/2e604a821638ed9982c4d87a95c6e7c0",
		"logoUrl": "https://d2q79iu7y748jz.cloudfront.net/s/_squarelogo/256x256/ca91152af76baeb6b5bbcf1b56aeaf22"
	},
	"companyOverviewLink": "https://www.indeed.com/cmp/Dr-Martens?campaignid=mobvjcmp&from=mobviewjob&tk=1h6p80pimj5ln805&fromjk=3c745bd1945cf2f4",
	"companyRating": 3.8,
	"companyReviewCount": 165,
	"displayTitle": "PART TIME SALES ASSOCIATE - HERALD SQUARE",
	"employerAssistEnabled": false,
	"employerResponsive": false,
	"expired": false,
	"extractedSalary": {
		"max": 19,
		"min": 19,
		"type": "hourly"
	},
	"featuredCompanyAttributes": {},
	"featuredEmployer": false,
	"featuredEmployerCandidate": false,
	"feedId": 605439,
	"formattedLocation": "New York, NY",
	"formattedRelativeTime": "30+ days ago",
	"highVolumeHiringModel": {
		"highVolumeHiring": false
	},
	"hiringEventJob": false,
	"indeedApplyEnabled": false,
	"indeedApplyable": false,
	"isJobVisited": false,
	"isMobileThirdPartyApplyable": true,
	"isNoResumeJob": false,
	"isSubsidiaryJob": false,
	"jobCardRequirementsModel": {
		"additionalRequirementsCount": 0,
		"requirementsHeaderShown": false
	},
	"jobLocationCity": "New York",
	"jobLocationState": "NY",
	"jobTypes": [
		"Part-time"
	],
	"locationCount": 4,
	"newJob": false,
	"normTitle": "Sales Associate",
	"openInterviewsInterviewsOnTheSpot": false,
	"openInterviewsJob": false,
	"openInterviewsOffersOnTheSpot": false,
	"openInterviewsPhoneJob": false,
	"overrideIndeedApplyText": true,
	"pubDate": 1683781200000,
	"rankingScoresModel": {
		"bid": 0,
		"eApply": 0.0402242,
		"eQualified": 0
	},
	"remoteLocation": false,
	"resumeMatch": false,
	"salarySnippet": {
		"currency": "USD",
		"salaryTextFormatted": false,
		"source": "EXTRACTION",
		"text": "$19 an hour"
	},
	"screenerQuestionsURL": "",
	"showAttainabilityBadge": false,
	"showCommutePromo": false,
	"showEarlyApply": false,
	"showJobType": false,
	"showRelativeDate": true,
	"showSponsoredLabel": false,
	"showStrongerAppliedLabel": false,
	"smartFillEnabled": false,
	"smbD2iEnabled": false,
	"snippet": "Punctual in adherence to scheduled shift times.\n Our Employee Assistance Program – for when times might get tough.\n Experience with MPOS a plus.",
	"sponsored": false,
	"taxoAttributes": [],
	"taxoAttributesDisplayLimit": 3,
	"taxoLogAttributes": [],
	"taxonomyAttributes": [
		{
			"attributes": [
				{
					"label": "Part-time",
					"suid": "75GKK"
				}
			],
			"label": "job-types"
		},
		{
			"attributes": [],
			"label": "shifts"
		},
		{
			"attributes": [],
			"label": "remote"
		},
		{
			"attributes": [
				{
					"label": "401(k)",
					"suid": "FVKX2"
				},
				{
					"label": "Flexible spending account",
					"suid": "G85UP"
				},
				{
					"label": "Paid time off",
					"suid": "HW4J4"
				},
				{
					"label": "Employee assistance program",
					"suid": "QXB7R"
				},
				{
					"label": "Employee discount",
					"suid": "SXFZX"
				}
			],
			"label": "benefits"
		},
		{
			"attributes": [
				{
					"label": "Part-time",
					"suid": "75GKK"
				}
			],
			"label": "job-types-cc"
		},
		{
			"attributes": [
				{
					"label": "Weekends as needed",
					"suid": "7SRRR"
				},
				{
					"label": "Evenings as needed",
					"suid": "EMGHB"
				},
				{
					"label": "Holidays",
					"suid": "VDB9U"
				}
			],
			"label": "schedules"
		}
	],
	"thirdPartyApplyUrl": "http://www.indeed.com//applystart?jk=3c745bd1945cf2f4&from=jobsearch&mvj=0&jobsearchTk=1h6p80n3himgp800&spon=0&adid=0&sjdu=uC1kB-aoihAFz7qa-DGUx620K0YMkjqgb3bZPFe3NNep7SYUvNPeLwghXp0UpRPmObpBerE5lIXdcJmE3tXQyw&vjfrom=vjs&astse=43035cc451b030c9&assa=4250",
	"title": "PART TIME SALES ASSOCIATE - HERALD SQUARE",
	"translatedAttributes": [],
	"translatedCmiJobTags": [
		"社割あり"
	],
	"truncatedCompany": "Dr Martens",
	"urgentlyHiring": false,
	"vjFeaturedEmployerCandidate": false,
	"workplaceInsights": [],
	"jobDescription": "THE STUFF THAT SETS YOU APART\n  You understand that as a Retail Sales Associates you are the face of our brand displaying knowledge and passion for our product, as you interface with our customers daily. You are results driven and motivated to achieve sales goals. You are a team player who thrives in a team-selling environment. You get the Dr. Martens brand and are excited to support the team in enhancing Dr. Martens’ footprint in the Americas region.\n \n  THE GIG\n  Selling Dr. Martens’ brand footwear, apparel, and accessories; and achieving personal sales goals and Key Performance (KPI) targets as set forth by Store Manager.\n \n   Delivering exceptional customer service by greeting store customers, offering product and brand knowledge, and helping to ensure and maximize sell-through, as needed.\n   Processing sales transactions accurately and promptly, meeting cash register systems requirements.\n   Organizing and maintaining merchandise to meet Brand Marketing guidelines and enhance product appeal\n   Replenishing the flow of merchandise from the stockroom to the sales floor.\n   Cleaning and maintaining retail store front, stock room, and all employee areas, including dusting, cleaning mirrors, and vacuuming.\n \n \n  YOUR FUNDAMENTAL QUALITIES\n  It’s never just a job at Dr. Martens. It’s a way of life. We live and breathe our Fundamentals – INTEGRITY. PROFESSIONAL. PASSIONATE. TEAM PLAYERS. They define who we are and how we get the job done. We believe each role is as unique as the person who does it. To join our team, you will also possess these qualities:\n \n   Previous retail sales experience, preferably in footwear or fashion apparel.\n   Experience in contributing to business goals and Key Performance Indicators (KPI) in a team environment, preferably in retail.\n   Excellent interpersonal skills and ability to communicate clearly and professionally in a team environment. Multilingual a plus.\n   Demonstrated understanding of basic math, including ability to calculate percentages required and ability to count back change.\n   Proficient in MS Office programs, retail/register systems, web-based programs, and computerized inventory systems preferred. Experience with MPOS a plus.\n   Ability to use initiative to accomplish tasks and detail oriented.\n   Willingness to work evenings, weekends, and holidays.\n   Punctual in adherence to scheduled shift times.\n   Ability to lift and carry up to 50 pounds and to carry shoe boxes while climbing a ladder and/or stairs.\n   International/domestic travel not required, 0 % of travel.\n   Connection with our Brand, The Stuff that Sets Us Apart and our Fundamental Qualities.\n \n \n  WHAT’S IN IT FOR YOU?\n \n   Pay information: $19.00/HR\n   Welcome to the brand pair of Docs\n   Employee discount of 65% off footwear and 50% on accessories\n   Rock the latest style with our seasonal pairs\n   Transit and parking flexible spending accounts\n   PTO and Sick Time\n   Our Employee Assistance Program – for when times might get tough\n   401(k) Pre-Tax and Roth Retirement Savings Plans with employer match\n   DM Foundation, supporting and empowering our communities around the world\n   Paid Volunteer Hours\n \n \n  At Dr. Martens, we are committed to creating an environment in which we can all be our best and bring our authentic selves to work. We encourage applications, regardless of race, color, religion, gender, gender identity or expression, sexual orientation, national origin, genetics, age, veteran status, or disability. Diverse and inclusive teams have a positive impact on our brand; helping us to speak authentically to our consumers.\n \n \n   We strive to develop a business where our people can thrive and feel empowered to express themselves. Because we believe everyone should feel supported and included, whatever their role in the Dr. Martens community.",
	"companyDetails": {
		"aboutSectionViewModel": {
			"aboutCeo": {
				"name": "Kenny Wilson, CEO Dr Martens PLC",
				"photoUrl": "https://d2q79iu7y748jz.cloudfront.net/s/_ceophoto/512x512/2c4021659dfe3d20c896a449e1df7993",
				"photoUrl48": "https://d2q79iu7y748jz.cloudfront.net/s/_ceophoto/48x48/2c4021659dfe3d20c896a449e1df7993",
				"photoUrl96": "https://d2q79iu7y748jz.cloudfront.net/s/_ceophoto/96x96/2c4021659dfe3d20c896a449e1df7993"
			},
			"aboutCompany": {
				"ceoApproval": 71,
				"description": "Our now-iconic air-cushioned sole was designed by a German inventor, Dr. Klaus Maertens. But while our sole may be German, our soul  is undeniably British. \r\n\r\nBritish shoe-makers, R Griggs and Co, bought the rights to that air-cushioned sole. Added in the iconic yellow stitch and grooves. Fastened the scripted heel-loop. And set about flogging these 8-eye boots to workmen.\r\n \r\nBut fate intervened. Dr. Martens may have been made for industry but, as it turns out, they were destined for the stage. Subverted early on by subcultures, they paved the way for a new kind of rebellious self-expression.\r\n \r\nFrom the punks of 70s London to the grungers of 90s Seattle, Dr. Martens have always stood with those who dare to be different. Subcultures may fade out and evolve but our alternative spirit is a constant. \r\n \r\nAnd as for what the future holds? \r\n \r\nWe have offices in London, Northampton, Portland, across EMEA and Asia, with an ever-expanding global retail portfolio. We have the respect of big-name fashion giants – think Supreme and Yohji Yamamoto – enabling us to engage in exciting partnerships season after season. \r\n \r\nWe want to mean something to everyone who laces up our boots: from the first-timers to the Docs veterans. Do you have what it takes to help us? We need ambitious, passionate, people – with rebel fire in their hearts. ",
				"employeeRange": "ERv1_1001_5000",
				"founded": 1960,
				"industry": "Retail & Wholesale",
				"name": "Dr Martens",
				"sectorNames": [
					"Retail & Wholesale"
				],
				"websiteUrl": {
					"text": "Dr Martens website",
					"url": "https://jobs.drmartens.com/"
				}
			}
		},
		"baseUrl": "/cmp/Dr-Martens",
		"benefitSectionViewModel": {
			"benefits": [
				{
					"benefit": "Employee discount",
					"category": "financial_perks"
				},
				{
					"benefit": "Retirement plan",
					"category": "retirement"
				},
				{
					"benefit": "Paid time off",
					"category": "leave"
				},
				{
					"benefit": "Flexible schedule",
					"category": "working_hours_regulation"
				},
				{
					"benefit": "Employee assistance program",
					"category": "others"
				},
				{
					"benefit": "Health insurance",
					"category": "insurance"
				},
				{
					"benefit": "Dental insurance",
					"category": "insurance"
				},
				{
					"benefit": "Life insurance",
					"category": "insurance"
				},
				{
					"benefit": "401k matching",
					"category": "retirement"
				},
				{
					"benefit": "Vision insurance",
					"category": "insurance"
				}
			],
			"companyName": "Dr Martens"
		},
		"breadcrumbs": {
			"breadcrumbs": [
				{
					"name": "Companies",
					"noFollow": false,
					"url": "https://www.indeed.com/companies"
				},
				{
					"name": "Retail & Wholesale",
					"noFollow": false,
					"url": "https://www.indeed.com/companies/best-Retail-&-Wholesale-companies"
				},
				{
					"name": "Dr Martens",
					"noFollow": false
				}
			]
		},
		"companyName": "Dr Martens",
		"companyPageFooter": {
			"enabledToShowUserFeedbackForm": false,
			"encodedFccId": "4ff833445a13c03b",
			"stickyJobsTabLink": {
				"jobsLink": "/cmp/Dr-Martens/jobs"
			}
		},
		"companyPageHeader": {
			"auroraLogoUrl": "https://d2q79iu7y748jz.cloudfront.net/s/_squarelogo/64x64/ca91152af76baeb6b5bbcf1b56aeaf22",
			"auroraLogoUrl2x": "https://d2q79iu7y748jz.cloudfront.net/s/_squarelogo/128x128/ca91152af76baeb6b5bbcf1b56aeaf22",
			"brandColor": "#FFFFFF",
			"companyHeader": {
				"happinessGrade": "GREAT",
				"happinessScore": 74,
				"name": "Dr Martens",
				"rating": 3.8,
				"reviewCount": 165,
				"reviewCountFormatted": "165",
				"reviewsUrl": "/cmp/Dr-Martens/reviews"
			},
			"followButton": {
				"brandColor": "#FFFFFF",
				"companyName": "Dr Martens",
				"disclaimerRequired": false,
				"encodedFccId": "4ff833445a13c03b",
				"followSource": "acmeSnapshot",
				"hashedCsrfToken": "e6e326ec67d388563de909ed5483461a",
				"loggedIn": false
			},
			"headerImage": {
				"headerImageUrl": "https://d2q79iu7y748jz.cloudfront.net/s/_headerimage/980x200/2e604a821638ed9982c4d87a95c6e7c0",
				"headerImageUrl2x": "https://d2q79iu7y748jz.cloudfront.net/s/_headerimage/1960x400/2e604a821638ed9982c4d87a95c6e7c0",
				"pageLanguage": "en"
			},
			"logoUrl": "https://d2q79iu7y748jz.cloudfront.net/s/_squarelogo/96x96/ca91152af76baeb6b5bbcf1b56aeaf22",
			"logoUrl2x": "https://d2q79iu7y748jz.cloudfront.net/s/_squarelogo/256x256/ca91152af76baeb6b5bbcf1b56aeaf22",
			"reviewCompanyUrl": "https://www.indeed.com/survey/mc?cid=4ff833445a13c03b&pkind=comp%3Aheader%3Awrite-a-review-button__targeted",
			"showPremiumHeader": false,
			"tabMenu": [
				{
					"name": "Snapshot",
					"nofollow": false,
					"selected": true,
					"turnstileElement": "overview-tab",
					"url": "/cmp/Dr-Martens"
				},
				{
					"name": "Why Join Us",
					"nofollow": false,
					"selected": false,
					"turnstileElement": "about-tab",
					"url": "/cmp/Dr-Martens/about"
				},
				{
					"count": "64",
					"name": "Jobs",
					"nofollow": false,
					"selected": false,
					"turnstileElement": "jobs-tab",
					"url": "/cmp/Dr-Martens/jobs"
				},
				{
					"count": "165",
					"name": "Reviews",
					"nofollow": false,
					"selected": false,
					"turnstileElement": "reviews-tab",
					"url": "/cmp/Dr-Martens/reviews"
				},
				{
					"count": "591",
					"name": "Salaries",
					"nofollow": false,
					"selected": false,
					"turnstileElement": "salaries-tab",
					"url": "/cmp/Dr-Martens/salaries"
				},
				{
					"name": "Benefits",
					"nofollow": false,
					"selected": false,
					"turnstileElement": "benefits-tab",
					"url": "/cmp/Dr-Martens/benefits"
				},
				{
					"count": "44",
					"name": "Q&A",
					"nofollow": false,
					"selected": false,
					"turnstileElement": "qna-tab",
					"url": "/cmp/Dr-Martens/faq"
				},
				{
					"name": "Interviews",
					"nofollow": false,
					"selected": false,
					"turnstileElement": "interviews-tab",
					"url": "/cmp/Dr-Martens/interviews"
				},
				{
					"count": "9",
					"name": "Photos",
					"nofollow": false,
					"selected": false,
					"turnstileElement": "photos-tab",
					"url": "/cmp/Dr-Martens/photos"
				}
			]
		},
		"educationCertsViewModel": {
			"educationCerts": []
		},
		"encodedFccId": "4ff833445a13c03b",
		"faqSectionViewModel": {
			"disableMarkup": false,
			"faqs": [
				{
					"answerLinks": [],
					"answerText": "Yes, Dr Martens has 64 open jobs. Before applying to Dr Martens, it’s a good idea to research the company, and read reviews from employees working there.",
					"questionText": "Is Dr Martens hiring now?"
				},
				{
					"answerLinks": [],
					"answerText": "People have reported that the interview at Dr Martens is easy. The interview process takes about a day or two. People have rated the overall interview experience as favorable.",
					"questionText": "Is it hard to get a job at Dr Martens?"
				},
				{
					"answerLinks": [],
					"answerText": "The interview process takes about a day or two. Overall, the interview experience is rated as favorable.",
					"questionText": "What is the hiring process at Dr Martens?"
				},
				{
					"answerLinks": [],
					"answerText": "The CEO of Dr Martens is Kenny Wilson, CEO Dr Martens PLC. Ratings from 45 employees, gives Kenny Wilson, CEO Dr Martens PLC an approval rating of 71%.",
					"questionText": "Who is the CEO of Dr Martens?"
				},
				{
					"answerLinks": [],
					"answerText": "Dr Martens has 1,001 to 5,000 employees.",
					"questionText": "How many employees does Dr Martens have?"
				},
				{
					"answerLinks": [],
					"answerText": "73% of survey respondents approved of the leadership response to COVID-19.",
					"questionText": "How has Dr Martens responded to COVID-19?"
				}
			]
		},
		"happinessModule": {
			"compositeScore": 74,
			"gradeBoundaries": [
				76,
				72,
				69,
				65
			],
			"individualRatings": [
				{
					"boundaries": [
						77,
						72,
						68,
						64
					],
					"caption": "How enjoyable people find their day-to-day life at work",
					"category": "Happiness",
					"grade": "GREAT",
					"questionCode": "HAPPINESS_HAPPINESS",
					"score": 74,
					"showIcon": true
				},
				{
					"boundaries": [
						81,
						76,
						72,
						68
					],
					"caption": "How valued people feel by their coworkers",
					"category": "Appreciation",
					"grade": "GREAT",
					"questionCode": "HAPPINESS_APPRECIATE",
					"score": 79,
					"showIcon": false
				},
				{
					"boundaries": [
						82,
						77,
						74,
						70
					],
					"caption": "How accomplished people feel at work",
					"category": "Achievement",
					"grade": "GREAT",
					"questionCode": "HAPPINESS_ACHIEVE",
					"score": 78,
					"showIcon": false
				},
				{
					"boundaries": [
						78,
						72,
						68,
						64
					],
					"caption": "How respectful people find their work environment",
					"category": "Inclusion",
					"grade": "EXCELLENT",
					"questionCode": "HAPPINESS_INCLUSIVE",
					"score": 78,
					"showIcon": false
				},
				{
					"boundaries": [
						82,
						77,
						73,
						69
					],
					"caption": "How meaningful people find their work",
					"category": "Purpose",
					"grade": "GOOD",
					"questionCode": "HAPPINESS_PURPOSE",
					"score": 76,
					"showIcon": false
				},
				{
					"boundaries": [
						76,
						72,
						68,
						64
					],
					"caption": "How fair people feel they are paid",
					"category": "Compensation",
					"grade": "EXCELLENT",
					"questionCode": "HAPPINESS_PAIDFAIR",
					"score": 76,
					"showIcon": false
				},
				{
					"boundaries": [
						80,
						75,
						71,
						67
					],
					"caption": "How encouraged people feel at work",
					"category": "Support",
					"grade": "GREAT",
					"questionCode": "HAPPINESS_SUPPORT",
					"score": 76,
					"showIcon": false
				},
				{
					"boundaries": [
						81,
						76,
						72,
						68
					],
					"caption": "How encouraged people feel to learn new skills",
					"category": "Learning",
					"grade": "GOOD",
					"questionCode": "HAPPINESS_LEARN",
					"score": 75,
					"showIcon": false
				},
				{
					"boundaries": [
						80,
						75,
						71,
						67
					],
					"caption": "How accommodating people find their work schedule",
					"category": "Flexibility",
					"grade": "GOOD",
					"questionCode": "HAPPINESS_FLEX",
					"score": 74,
					"showIcon": false
				},
				{
					"boundaries": [
						76,
						71,
						67,
						62
					],
					"caption": "How supportive people find their manager",
					"category": "Management",
					"grade": "GREAT",
					"questionCode": "HAPPINESS_MANAGER",
					"score": 74,
					"showIcon": false
				},
				{
					"boundaries": [
						75,
						70,
						66,
						62
					],
					"caption": "How content people feel with the way things are at work\n",
					"category": "Satisfaction",
					"grade": "GREAT",
					"questionCode": "HAPPINESS_SATISFIED",
					"score": 74,
					"showIcon": false
				},
				{
					"boundaries": [
						76,
						70,
						66,
						61
					],
					"caption": "How safe people feel around their coworkers",
					"category": "Trust",
					"grade": "GREAT",
					"questionCode": "HAPPINESS_TRUST",
					"score": 73,
					"showIcon": false
				},
				{
					"boundaries": [
						75,
						70,
						66,
						61
					],
					"caption": "How accepted people feel at work",
					"category": "Belonging",
					"grade": "GREAT",
					"questionCode": "HAPPINESS_BELONGING",
					"score": 73,
					"showIcon": false
				},
				{
					"boundaries": [
						79,
						74,
						70,
						66
					],
					"caption": "How energized people feel by their work",
					"category": "Energy",
					"grade": "GOOD",
					"questionCode": "HAPPINESS_ENERGIZED",
					"score": 72,
					"showIcon": false
				},
				{
					"boundaries": [
						74,
						70,
						67,
						63
					],
					"caption": "How manageable people find their work stress\n",
					"category": "Stress-free",
					"grade": "GREAT",
					"questionCode": "HAPPINESS_STRESS",
					"score": 70,
					"showIcon": false
				}
			],
			"numberOfResponses": 100,
			"numberOfResponsesFormatted": "100",
			"surveyStatements": [
				{
					"category": "Happiness",
					"surveyStatement": "I feel happy at work most of the time."
				},
				{
					"category": "Compensation",
					"surveyStatement": "I am paid fairly for my work."
				},
				{
					"category": "Achievement",
					"surveyStatement": "I am achieving most of my goals at work."
				},
				{
					"category": "Appreciation",
					"surveyStatement": "There are people at work who appreciate me as a person."
				},
				{
					"category": "Energy",
					"surveyStatement": "In most of my work tasks, I feel energized."
				},
				{
					"category": "Support",
					"surveyStatement": "There are people at work who give me support and encouragement."
				},
				{
					"category": "Purpose",
					"surveyStatement": "My work has a clear sense of purpose."
				},
				{
					"category": "Learning",
					"surveyStatement": "I often learn something at work."
				},
				{
					"category": "Inclusion",
					"surveyStatement": "My work environment feels inclusive and respectful of all people."
				},
				{
					"category": "Flexibility",
					"surveyStatement": "My work has the time and location flexibility I need."
				},
				{
					"category": "Trust",
					"surveyStatement": "I can trust people in my company."
				},
				{
					"category": "Belonging",
					"surveyStatement": "I feel a sense of belonging in my company."
				},
				{
					"category": "Management",
					"surveyStatement": "My manager helps me succeed."
				},
				{
					"category": "Satisfaction",
					"surveyStatement": "Overall, I am completely satisfied with my job."
				},
				{
					"category": "Stress-free",
					"surveyStatement": "I don't feel stressed at work most of the time."
				}
			]
		},
		"interviewsSectionViewModel": {
			"formattedCount": "62",
			"interviewQuestions": {
				"answers": [
					{
						"answerText": {
							"languageTag": "en",
							"text": "Why would we pick you \nwhat's  your strength\nHow long  you plan to stay what's your  goals  "
						},
						"jobTitle": "Shipping and Receiving",
						"location": "Portland, OR",
						"submissionDate": "August 8, 2022"
					},
					{
						"answerText": {
							"languageTag": "en",
							"text": "If I was open minded with working in warehouse and learning how use scanners."
						},
						"jobTitle": "Packing and Shipping",
						"location": "Portland, OR",
						"submissionDate": "March 24, 2020"
					}
				],
				"companyName": "Dr Martens",
				"interviewQuestionURL": "/cmp/Dr-Martens/faq/what-questions-did-they-ask-during-your-interview-at-dr-martens?quid=1dd7g2n4cb8ba800"
			},
			"summaryStory": {
				"anyDataAvailable": true,
				"difficultyCard": {
					"answerCount": 62,
					"result": "EASY"
				},
				"durationCard": {
					"answerCount": 43,
					"text": "About a day or two"
				},
				"experienceCard": {
					"answerCount": 33,
					"result": "FAVORABLE"
				}
			}
		},
		"jobTitleSectionViewModel": {
			"jobTitles": [
				{
					"displayName": "Sales Associate",
					"jobCount": 15,
					"reviewRating": 4.5333333015441895,
					"url": "/cmp/Dr-Martens/job-titles/Sales-Associate"
				},
				{
					"displayName": "Sales Manager",
					"jobCount": 5,
					"reviewRating": 4.599999904632568,
					"url": "/cmp/Dr-Martens/job-titles/Sales-Manager"
				},
				{
					"displayName": "Store Manager",
					"jobCount": 3,
					"reviewRating": 2.3333332538604736,
					"url": "/cmp/Dr-Martens/job-titles/Store-Manager"
				},
				{
					"displayName": "Supervisor",
					"jobCount": 3,
					"reviewRating": 3.3333332538604736,
					"url": "/cmp/Dr-Martens/job-titles/Supervisor"
				},
				{
					"displayName": "Warehouse Worker",
					"jobCount": 3,
					"reviewRating": 4.333333492279053,
					"url": "/cmp/Dr-Martens/job-titles/Warehouse-Worker"
				},
				{
					"displayName": "Operator",
					"jobCount": 2,
					"reviewRating": 2,
					"url": "/cmp/Dr-Martens/job-titles/Operator"
				}
			]
		},
		"jobsSectionViewModel": {
			"baseUrl": "/cmp/Dr-Martens",
			"companyLogoUrl": "https://d2q79iu7y748jz.cloudfront.net/s/_squarelogo/256x256/ca91152af76baeb6b5bbcf1b56aeaf22",
			"companyName": "Dr Martens",
			"jobCategories": [
				{
					"displayName": "Sales",
					"jobCount": 45,
					"key": "sales"
				},
				{
					"displayName": "Retail",
					"jobCount": 10,
					"key": "retail"
				},
				{
					"displayName": "Administrative Assistance",
					"jobCount": 4,
					"key": "admin"
				},
				{
					"displayName": "Banking & Finance",
					"jobCount": 2,
					"key": "finance"
				},
				{
					"displayName": "Human Resources",
					"jobCount": 1,
					"key": "hr"
				},
				{
					"displayName": "Management",
					"jobCount": 1,
					"key": "management"
				},
				{
					"displayName": "Marketing",
					"jobCount": 1,
					"key": "marketing"
				}
			],
			"jobLocations": [
				{
					"canonicalUrl": "https://www.indeed.com/cmp/Dr-Martens/jobs/l-New-York,-NY",
					"jobCount": 12,
					"name": "New York, NY"
				},
				{
					"canonicalUrl": "https://www.indeed.com/cmp/Dr-Martens/jobs/l-Portland,-OR",
					"jobCount": 9,
					"name": "Portland, OR"
				},
				{
					"canonicalUrl": "https://www.indeed.com/cmp/Dr-Martens/jobs/l-Houston,-TX",
					"jobCount": 5,
					"name": "Houston, TX"
				},
				{
					"canonicalUrl": "https://www.indeed.com/cmp/Dr-Martens/jobs/l-Aventura,-FL",
					"jobCount": 4,
					"name": "Aventura, FL"
				},
				{
					"canonicalUrl": "https://www.indeed.com/cmp/Dr-Martens/jobs/l-King-of-Prussia,-PA",
					"jobCount": 4,
					"name": "King of Prussia, PA"
				},
				{
					"canonicalUrl": "https://www.indeed.com/cmp/Dr-Martens/jobs/l-Tysons,-VA",
					"jobCount": 4,
					"name": "Tysons, VA"
				},
				{
					"canonicalUrl": "https://www.indeed.com/cmp/Dr-Martens/jobs/l-Santa-Monica,-CA",
					"jobCount": 2,
					"name": "Santa Monica, CA"
				},
				{
					"canonicalUrl": "https://www.indeed.com/cmp/Dr-Martens/jobs/l-Los-Angeles,-CA",
					"jobCount": 2,
					"name": "Los Angeles, CA"
				},
				{
					"canonicalUrl": "https://www.indeed.com/cmp/Dr-Martens/jobs/l-Edison,-NJ",
					"jobCount": 2,
					"name": "Edison, NJ"
				},
				{
					"canonicalUrl": "https://www.indeed.com/cmp/Dr-Martens/jobs/l-Atlanta,-GA",
					"jobCount": 2,
					"name": "Atlanta, GA"
				}
			],
			"jobTitles": [
				{
					"displayName": "Sales Associate",
					"jobCount": 25,
					"url": "/cmp/Dr-Martens/jobs/q-Sales-Associate"
				},
				{
					"displayName": "Sales Manager",
					"jobCount": 20,
					"url": "/cmp/Dr-Martens/jobs/q-Sales-Manager"
				},
				{
					"displayName": "Assistant Store Manager",
					"jobCount": 5,
					"url": "/cmp/Dr-Martens/jobs/q-Assistant-Store-Manager"
				}
			],
			"location": "",
			"locationAllJobsUrl": "/cmp/Dr-Martens/jobs",
			"locationJobs": [
				{
					"clickUrl": "/rc/clk?jk=6aceb01f25408da2&from=company&tk=1h6p80q87iol1802&log=1",
					"formattedRelativeTime": "30+ days ago",
					"indeedApply": false,
					"jobKey": "6aceb01f25408da2",
					"jobTypes": [
						"Part-time"
					],
					"location": "Ohio",
					"salarySnippet": "$15 an hour",
					"sponsored": false,
					"title": "PART TIME SALES ASSOCIATE - KENWOOD",
					"urgentHire": false,
					"url": "/rc/clk?jk=6aceb01f25408da2&from=company&tk=1h6p80q87iol1802"
				},
				{
					"clickUrl": "/rc/clk?jk=12001f67d340d1ea&from=company&tk=1h6p80q87iol1802&log=1",
					"formattedRelativeTime": "5 days ago",
					"indeedApply": false,
					"jobKey": "12001f67d340d1ea",
					"jobTypes": [
						"Part-time"
					],
					"location": "New York, NY",
					"sponsored": false,
					"title": "PART TIME SALES ASSOCIATE - LEXINGTON",
					"urgentHire": false,
					"url": "/rc/clk?jk=12001f67d340d1ea&from=company&tk=1h6p80q87iol1802"
				},
				{
					"clickUrl": "/rc/clk?jk=9776da7dba7ab3de&from=company&tk=1h6p80q87iol1802&log=1",
					"formattedRelativeTime": "30+ days ago",
					"indeedApply": false,
					"jobKey": "9776da7dba7ab3de",
					"jobTypes": [
						"Part-time"
					],
					"location": "New York, NY",
					"salarySnippet": "$19 an hour",
					"sponsored": false,
					"title": "PART TIME SALES ASSOCIATE - SOHO",
					"urgentHire": false,
					"url": "/rc/clk?jk=9776da7dba7ab3de&from=company&tk=1h6p80q87iol1802"
				},
				{
					"clickUrl": "/rc/clk?jk=f6e4f85b2c33d8c6&from=company&tk=1h6p80q87iol1802&log=1",
					"formattedRelativeTime": "30+ days ago",
					"indeedApply": false,
					"jobKey": "f6e4f85b2c33d8c6",
					"jobTypes": [
						"Part-time"
					],
					"location": "New York, NY",
					"sponsored": false,
					"title": "PART TIME SALES ASSOCIATE - WILLIAMSBURG",
					"urgentHire": false,
					"url": "/rc/clk?jk=f6e4f85b2c33d8c6&from=company&tk=1h6p80q87iol1802"
				},
				{
					"clickUrl": "/rc/clk?jk=7d81a82cb7a140bb&from=company&tk=1h6p80q87iol1802&log=1",
					"formattedRelativeTime": "30+ days ago",
					"indeedApply": false,
					"jobKey": "7d81a82cb7a140bb",
					"jobTypes": [
						"Part-time"
					],
					"location": "New York, NY",
					"salarySnippet": "$23.75 an hour",
					"sponsored": false,
					"title": "PART TIME SALES SUPERVISOR - QUEENS",
					"urgentHire": false,
					"url": "/rc/clk?jk=7d81a82cb7a140bb&from=company&tk=1h6p80q87iol1802"
				},
				{
					"clickUrl": "/rc/clk?jk=434b3151a0f64b78&from=company&tk=1h6p80q87iol1802&log=1",
					"formattedRelativeTime": "30+ days ago",
					"indeedApply": false,
					"jobKey": "434b3151a0f64b78",
					"jobTypes": [
						"Part-time"
					],
					"location": "Houston, TX",
					"sponsored": false,
					"title": "PART TIME SALES ASSOCIATE - BAYBROOK",
					"urgentHire": false,
					"url": "/rc/clk?jk=434b3151a0f64b78&from=company&tk=1h6p80q87iol1802"
				},
				{
					"clickUrl": "/rc/clk?jk=e9b57568fae1ddc0&from=company&tk=1h6p80q87iol1802&log=1",
					"formattedRelativeTime": "30+ days ago",
					"indeedApply": false,
					"jobKey": "e9b57568fae1ddc0",
					"jobTypes": [
						"Full-time"
					],
					"location": "Glendale, AZ",
					"salarySnippet": "$23.75 an hour",
					"sponsored": false,
					"title": "FULL TIME STOCK SUPERVISOR - GLENDALE",
					"urgentHire": false,
					"url": "/rc/clk?jk=e9b57568fae1ddc0&from=company&tk=1h6p80q87iol1802"
				},
				{
					"clickUrl": "/rc/clk?jk=19ac6d1a5db3e0ce&from=company&tk=1h6p80q87iol1802&log=1",
					"formattedRelativeTime": "30+ days ago",
					"indeedApply": false,
					"jobKey": "19ac6d1a5db3e0ce",
					"jobTypes": [
						"Part-time"
					],
					"location": "New York, NY",
					"salarySnippet": "$23.75 an hour",
					"sponsored": false,
					"title": "PART TIME SALES SUPERVISOR - SOHO",
					"urgentHire": false,
					"url": "/rc/clk?jk=19ac6d1a5db3e0ce&from=company&tk=1h6p80q87iol1802"
				},
				{
					"clickUrl": "/rc/clk?jk=c8a5e6b8fa53374a&from=company&tk=1h6p80q87iol1802&log=1",
					"formattedRelativeTime": "30+ days ago",
					"indeedApply": false,
					"jobKey": "c8a5e6b8fa53374a",
					"jobTypes": [
						"Part-time"
					],
					"location": "King of Prussia, PA",
					"sponsored": false,
					"title": "PART TIME SALES ASSOCIATE - KING OF PRUSSIA",
					"urgentHire": false,
					"url": "/rc/clk?jk=c8a5e6b8fa53374a&from=company&tk=1h6p80q87iol1802"
				},
				{
					"clickUrl": "/rc/clk?jk=9cbf83bf23ba4d9b&from=company&tk=1h6p80q87iol1802&log=1",
					"formattedRelativeTime": "27 days ago",
					"indeedApply": false,
					"jobKey": "9cbf83bf23ba4d9b",
					"jobTypes": [
						"Part-time"
					],
					"location": "Los Angeles, CA",
					"sponsored": false,
					"title": "PART TIME SALES SUPERVISOR - ABBOT KINNEY",
					"urgentHire": false,
					"url": "/rc/clk?jk=9cbf83bf23ba4d9b&from=company&tk=1h6p80q87iol1802"
				},
				{
					"clickUrl": "/rc/clk?jk=bccf305a71fbcaa4&from=company&tk=1h6p80q87iol1802&log=1",
					"formattedRelativeTime": "30+ days ago",
					"indeedApply": false,
					"jobKey": "bccf305a71fbcaa4",
					"jobTypes": [
						"Full-time"
					],
					"location": "King of Prussia, PA",
					"sponsored": false,
					"title": "FULL TIME SALES SUPERVISOR - KING OF PRUSSIA",
					"urgentHire": false,
					"url": "/rc/clk?jk=bccf305a71fbcaa4&from=company&tk=1h6p80q87iol1802"
				},
				{
					"clickUrl": "/rc/clk?jk=70b36f8039bc641c&from=company&tk=1h6p80q87iol1802&log=1",
					"formattedRelativeTime": "30+ days ago",
					"indeedApply": false,
					"jobKey": "70b36f8039bc641c",
					"jobTypes": [
						"Part-time"
					],
					"location": "Miami Beach, FL",
					"salarySnippet": "$15 an hour",
					"sponsored": false,
					"title": "PART TIME STOCK ASSOCIATE - LINCOLN ROAD",
					"urgentHire": false,
					"url": "/rc/clk?jk=70b36f8039bc641c&from=company&tk=1h6p80q87iol1802"
				},
				{
					"clickUrl": "/rc/clk?jk=ad2cead777d47e76&from=company&tk=1h6p80q87iol1802&log=1",
					"formattedRelativeTime": "15 days ago",
					"indeedApply": false,
					"jobKey": "ad2cead777d47e76",
					"jobTypes": [
						"Full-time"
					],
					"location": "Portland, OR",
					"sponsored": false,
					"title": "ADMINISTRATIVE ASSISTANT US",
					"urgentHire": false,
					"url": "/rc/clk?jk=ad2cead777d47e76&from=company&tk=1h6p80q87iol1802"
				},
				{
					"clickUrl": "/rc/clk?jk=4275dae79469202a&from=company&tk=1h6p80q87iol1802&log=1",
					"formattedRelativeTime": "14 days ago",
					"indeedApply": false,
					"jobKey": "4275dae79469202a",
					"jobTypes": [
						"Full-time"
					],
					"location": "Portland, OR",
					"sponsored": false,
					"title": "SALES BUSINESS PLANNER",
					"urgentHire": false,
					"url": "/rc/clk?jk=4275dae79469202a&from=company&tk=1h6p80q87iol1802"
				},
				{
					"clickUrl": "/rc/clk?jk=bde4c79ddcee75ba&from=company&tk=1h6p80q87iol1802&log=1",
					"formattedRelativeTime": "30+ days ago",
					"indeedApply": false,
					"jobKey": "bde4c79ddcee75ba",
					"jobTypes": [],
					"location": "New York, NY",
					"salarySnippet": "$30.19 an hour",
					"sponsored": false,
					"title": "ASSISTANT STORE MANAGER - SOHO",
					"urgentHire": false,
					"url": "/rc/clk?jk=bde4c79ddcee75ba&from=company&tk=1h6p80q87iol1802"
				},
				{
					"clickUrl": "/rc/clk?jk=44b09a76f1fc1c58&from=company&tk=1h6p80q87iol1802&log=1",
					"formattedRelativeTime": "28 days ago",
					"indeedApply": false,
					"jobKey": "44b09a76f1fc1c58",
					"jobTypes": [
						"Full-time"
					],
					"location": "Portland, OR",
					"sponsored": false,
					"title": "SUPPLY & DEMAND PLANNING DIRECTOR",
					"urgentHire": false,
					"url": "/rc/clk?jk=44b09a76f1fc1c58&from=company&tk=1h6p80q87iol1802"
				},
				{
					"clickUrl": "/rc/clk?jk=c09cb14d6ed0d676&from=company&tk=1h6p80q87iol1802&log=1",
					"formattedRelativeTime": "30+ days ago",
					"indeedApply": false,
					"jobKey": "c09cb14d6ed0d676",
					"jobTypes": [],
					"location": "Aventura, FL",
					"salarySnippet": "$26.86 an hour",
					"sponsored": false,
					"title": "ASSISTANT STORE MANAGER - AVENTURA",
					"urgentHire": false,
					"url": "/rc/clk?jk=c09cb14d6ed0d676&from=company&tk=1h6p80q87iol1802"
				},
				{
					"clickUrl": "/rc/clk?jk=3b0e4cd36b210765&from=company&tk=1h6p80q87iol1802&log=1",
					"formattedRelativeTime": "26 days ago",
					"indeedApply": false,
					"jobKey": "3b0e4cd36b210765",
					"jobTypes": [
						"Full-time"
					],
					"location": "Remote",
					"sponsored": false,
					"title": "VP OF WHOLESALE, AMERICAS",
					"urgentHire": false,
					"url": "/rc/clk?jk=3b0e4cd36b210765&from=company&tk=1h6p80q87iol1802"
				},
				{
					"clickUrl": "/rc/clk?jk=3f6a24f8e9c94137&from=company&tk=1h6p80q87iol1802&log=1",
					"formattedRelativeTime": "30+ days ago",
					"indeedApply": false,
					"jobKey": "3f6a24f8e9c94137",
					"jobTypes": [],
					"location": "Atlanta, GA",
					"salarySnippet": "$25 an hour",
					"sponsored": false,
					"title": "ASSISTANT STORE MANAGER - LENOX",
					"urgentHire": false,
					"url": "/rc/clk?jk=3f6a24f8e9c94137&from=company&tk=1h6p80q87iol1802"
				},
				{
					"clickUrl": "/rc/clk?jk=bcc58d040964c80a&from=company&tk=1h6p80q87iol1802&log=1",
					"formattedRelativeTime": "2 hours ago",
					"indeedApply": false,
					"jobKey": "bcc58d040964c80a",
					"jobTypes": [
						"Full-time"
					],
					"location": "Portland, OR",
					"sponsored": false,
					"title": "ECOMMERCE SITE MERCHANDISER",
					"urgentHire": false,
					"url": "/rc/clk?jk=bcc58d040964c80a&from=company&tk=1h6p80q87iol1802"
				}
			],
			"moreLinkUrl": "/cmp/Dr-Martens/jobs",
			"totalJobCount": 64,
			"totalLocationJobCount": 64
		},
		"locationsSectionViewModel": {
			"locations": [
				{
					"href": "/cmp/Dr-Martens/locations/OR/Portland",
					"name": "Portland, OR",
					"reviewRating": 3.4827585220336914
				},
				{
					"href": "/cmp/Dr-Martens/locations/NY/New%20York",
					"name": "New York, NY",
					"reviewRating": 4.4285712242126465
				},
				{
					"href": "/cmp/Dr-Martens/locations/CA/Los%20Angeles",
					"name": "Los Angeles, CA",
					"reviewRating": 3.75
				},
				{
					"href": "/cmp/Dr-Martens/locations/IL/Chicago",
					"name": "Chicago, IL",
					"reviewRating": 4.333333492279053
				},
				{
					"href": "/cmp/Dr-Martens/locations/NJ/Elizabeth",
					"name": "Elizabeth, NJ",
					"reviewRating": 4.5
				},
				{
					"href": "/cmp/Dr-Martens/locations/CA/San%20Francisco",
					"name": "San Francisco, CA",
					"reviewRating": 4.5
				}
			]
		},
		"qnaSectionViewModel": {
			"baseUrl": "/cmp/Dr-Martens",
			"categoryQuestions": [
				{
					"category": "Popular questions",
					"questions": [
						{
							"baseUrl": "/cmp/Dr-Martens",
							"companyName": "Dr Martens",
							"creationDate": "2022-08-21T21:08Z",
							"formattedCreationDateTime": "August 21, 2022",
							"official": false,
							"questionText": {
								"text": "What is the promotion process like at Dr Martens?"
							},
							"questionUid": "1gb13npcfjgev801",
							"questionUrl": "faq/what-is-the-promotion-process-like-at-dr-martens?quid=1gb13npcfjgev801",
							"topAnswer": {
								"answerText": {
									"languageTag": "en",
									"text": "There’s a development plan and work with your managers "
								},
								"answerUid": "1gp72mtncii1l801",
								"creationDate": "2023-02-14T04:25Z",
								"formattedCreationDateTime": "February 13, 2023",
								"jobTitle": "Store Manager",
								"location": "Austin, TX",
								"official": false
							},
							"totalAnswerCount": 7
						},
						{
							"baseUrl": "/cmp/Dr-Martens",
							"companyName": "Dr Martens",
							"creationDate": "2022-08-21T21:07Z",
							"formattedCreationDateTime": "August 21, 2022",
							"official": false,
							"questionText": {
								"text": "How often do you get a raise at Dr Martens?"
							},
							"questionUid": "1gb13ngd9jgev801",
							"questionUrl": "faq/how-often-do-you-get-a-raise-at-dr-martens?quid=1gb13ngd9jgev801",
							"topAnswer": {
								"answerText": {
									"languageTag": "en",
									"text": "Yearly"
								},
								"answerUid": "1gvkfaossghps801",
								"creationDate": "2023-05-04T22:50Z",
								"formattedCreationDateTime": "May 4, 2023",
								"jobTitle": "Sales Associate",
								"location": "Schaumburg, IL",
								"official": false
							},
							"totalAnswerCount": 7
						},
						{
							"baseUrl": "/cmp/Dr-Martens",
							"companyName": "Dr Martens",
							"creationDate": "2023-01-31T02:27Z",
							"formattedCreationDateTime": "January 30, 2023",
							"official": false,
							"questionText": {
								"text": "What is covered by the health insurance at Dr Martens?"
							},
							"questionUid": "1go2qctnujgfq801",
							"questionUrl": "faq/what-is-covered-by-the-health-insurance-at-dr-martens?quid=1go2qctnujgfq801",
							"topAnswer": {
								"answerText": {
									"languageTag": "en",
									"text": "No working from home"
								},
								"answerUid": "1h53924hj2cmp001",
								"creationDate": "2023-07-11T20:07Z",
								"formattedCreationDateTime": "July 11, 2023",
								"jobTitle": "Sales Associate",
								"location": "Tulalip, WA",
								"official": false
							},
							"totalAnswerCount": 3
						}
					]
				},
				{
					"category": "Hiring Process",
					"questions": [
						{
							"baseUrl": "/cmp/Dr-Martens",
							"companyName": "Dr Martens",
							"creationDate": "2022-08-21T21:08Z",
							"formattedCreationDateTime": "August 21, 2022",
							"official": false,
							"questionText": {
								"text": "What is the promotion process like at Dr Martens?"
							},
							"questionUid": "1gb13npcfjgev801",
							"questionUrl": "faq/what-is-the-promotion-process-like-at-dr-martens?quid=1gb13npcfjgev801",
							"topAnswer": {
								"answerText": {
									"languageTag": "en",
									"text": "There’s a development plan and work with your managers "
								},
								"answerUid": "1gp72mtncii1l801",
								"creationDate": "2023-02-14T04:25Z",
								"formattedCreationDateTime": "February 13, 2023",
								"jobTitle": "Store Manager",
								"location": "Austin, TX",
								"official": false
							},
							"totalAnswerCount": 7
						},
						{
							"baseUrl": "/cmp/Dr-Martens",
							"companyName": "Dr Martens",
							"creationDate": "2021-08-10T18:11Z",
							"formattedCreationDateTime": "August 10, 2021",
							"official": false,
							"questionText": {
								"text": "How long does it take to get an interview after you apply at Dr Martens?"
							},
							"questionUid": "1fcok64jqhimt800",
							"questionUrl": "faq/how-long-does-it-take-to-get-an-interview-after-you-apply-at-dr-martens?quid=1fcok64jqhimt800",
							"topAnswer": {
								"answerText": {
									"languageTag": "en",
									"text": "Applied and a couple of days later got an interview. nothing special. very simple. "
								},
								"answerUid": "1fuldn1lqpi1g801",
								"creationDate": "2022-03-21T05:03Z",
								"currentlyEmployed": false,
								"formattedCreationDateTime": "March 21, 2022",
								"jobTitle": "Sales Associate",
								"location": "Studio City, CA",
								"official": false
							},
							"totalAnswerCount": 2
						},
						{
							"baseUrl": "/cmp/Dr-Martens",
							"companyName": "Dr Martens",
							"creationDate": "2022-11-09T05:53Z",
							"formattedCreationDateTime": "November 8, 2022",
							"official": false,
							"questionText": {
								"text": "Describe the drug test process at Dr Martens, if there is one"
							},
							"questionUid": "1ghdf6a14hbh5801",
							"questionUrl": "faq/describe-the-drug-test-process-at-dr-martens-if-there-is-one?quid=1ghdf6a14hbh5801",
							"topAnswer": {
								"answerText": {
									"languageTag": "en",
									"text": "Drug tests occur onsite immediately following any accident involving a machine in motion "
								},
								"answerUid": "1ghdf6a14hbh5801",
								"creationDate": "2022-11-09T05:53Z",
								"currentlyEmployed": false,
								"formattedCreationDateTime": "November 8, 2022",
								"jobTitle": "Inbound Supervisor",
								"location": "Portland, OR",
								"official": false
							},
							"totalAnswerCount": 1
						}
					]
				},
				{
					"category": "Benefits",
					"questions": [
						{
							"baseUrl": "/cmp/Dr-Martens",
							"companyName": "Dr Martens",
							"creationDate": "2023-01-31T02:27Z",
							"formattedCreationDateTime": "January 30, 2023",
							"official": false,
							"questionText": {
								"text": "What is covered by the health insurance at Dr Martens?"
							},
							"questionUid": "1go2qctnujgfq801",
							"questionUrl": "faq/what-is-covered-by-the-health-insurance-at-dr-martens?quid=1go2qctnujgfq801",
							"topAnswer": {
								"answerText": {
									"languageTag": "en",
									"text": "No working from home"
								},
								"answerUid": "1h53924hj2cmp001",
								"creationDate": "2023-07-11T20:07Z",
								"formattedCreationDateTime": "July 11, 2023",
								"jobTitle": "Sales Associate",
								"location": "Tulalip, WA",
								"official": false
							},
							"totalAnswerCount": 3
						},
						{
							"baseUrl": "/cmp/Dr-Martens",
							"companyName": "Dr Martens",
							"creationDate": "2023-03-06T21:03Z",
							"formattedCreationDateTime": "March 6, 2023",
							"official": false,
							"questionText": {
								"text": "What is covered by the life insurance at Dr Martens?"
							},
							"questionUid": "1gqsbosf2h7hk801",
							"questionUrl": "faq/what-is-covered-by-the-life-insurance-at-dr-martens?quid=1gqsbosf2h7hk801",
							"topAnswer": {
								"answerText": {
									"languageTag": "en",
									"text": "No insurance "
								},
								"answerUid": "1h5392dnq2cmp000",
								"creationDate": "2023-07-11T20:07Z",
								"formattedCreationDateTime": "July 11, 2023",
								"jobTitle": "Sales Associate",
								"location": "Tulalip, WA",
								"official": false
							},
							"totalAnswerCount": 2
						},
						{
							"baseUrl": "/cmp/Dr-Martens",
							"companyName": "Dr Martens",
							"creationDate": "2023-02-14T01:04Z",
							"formattedCreationDateTime": "February 13, 2023",
							"official": false,
							"questionText": {
								"text": "What benefits does Dr Martens offer?"
							},
							"questionUid": "1gp6n7msri9me801",
							"questionUrl": "faq/what-benefits-does-dr-martens-offer?quid=1gp6n7msri9me801",
							"topAnswer": {
								"answerText": {
									"languageTag": "en",
									"text": "401k, health insurance, PTO, sick pay"
								},
								"answerUid": "1guremi3ais33801",
								"creationDate": "2023-04-25T05:38Z",
								"formattedCreationDateTime": "April 25, 2023",
								"jobTitle": "Sales Associate",
								"location": "Schaumburg, IL",
								"official": false
							},
							"totalAnswerCount": 2
						}
					]
				},
				{
					"category": "Interviews",
					"questions": [
						{
							"baseUrl": "/cmp/Dr-Martens",
							"companyName": "Dr Martens",
							"creationDate": "2020-03-04T16:52Z",
							"formattedCreationDateTime": "March 4, 2020",
							"official": false,
							"questionText": {
								"text": "What tips or advice would you give to someone interviewing at Dr Martens?"
							},
							"questionUid": "1e2j7d345olrc800",
							"questionUrl": "faq/what-tips-or-advice-would-you-give-to-someone-interviewing-at-dr-martens?quid=1e2j7d345olrc800",
							"topAnswer": {
								"answerText": {
									"languageTag": "en",
									"text": "Make sure you’re comfortable going up to people and talking to them and portray that in your interview as well "
								},
								"answerUid": "1guoeer5ritlp801",
								"creationDate": "2023-04-24T01:36Z",
								"formattedCreationDateTime": "April 23, 2023",
								"jobTitle": "Sales Associate",
								"location": "Schaumburg, IL",
								"official": false
							},
							"totalAnswerCount": 3
						},
						{
							"baseUrl": "/cmp/Dr-Martens",
							"companyName": "Dr Martens",
							"creationDate": "2021-08-10T18:11Z",
							"formattedCreationDateTime": "August 10, 2021",
							"official": false,
							"questionText": {
								"text": "How long does it take to get an interview after you apply at Dr Martens?"
							},
							"questionUid": "1fcok64jqhimt800",
							"questionUrl": "faq/how-long-does-it-take-to-get-an-interview-after-you-apply-at-dr-martens?quid=1fcok64jqhimt800",
							"topAnswer": {
								"answerText": {
									"languageTag": "en",
									"text": "Applied and a couple of days later got an interview. nothing special. very simple. "
								},
								"answerUid": "1fuldn1lqpi1g801",
								"creationDate": "2022-03-21T05:03Z",
								"currentlyEmployed": false,
								"formattedCreationDateTime": "March 21, 2022",
								"jobTitle": "Sales Associate",
								"location": "Studio City, CA",
								"official": false
							},
							"totalAnswerCount": 2
						},
						{
							"baseUrl": "/cmp/Dr-Martens",
							"companyName": "Dr Martens",
							"creationDate": "2021-07-05T11:48Z",
							"formattedCreationDateTime": "July 5, 2021",
							"official": false,
							"questionText": {
								"text": "How should I prepare for an interview at Dr Martens?"
							},
							"questionUid": "1f9r7ulrgnpjo800",
							"questionUrl": "faq/how-should-i-prepare-for-an-interview-at-dr-martens?quid=1f9r7ulrgnpjo800",
							"topAnswer": {
								"answerText": {
									"languageTag": "en",
									"text": "Discuss prior experience with customer service and experience in fashion. "
								},
								"answerUid": "1fcok64jghimt800",
								"creationDate": "2021-08-10T18:11Z",
								"currentlyEmployed": true,
								"formattedCreationDateTime": "August 10, 2021",
								"jobTitle": "Part Time Sales Associate",
								"location": "Minneapolis, MN",
								"official": false
							},
							"totalAnswerCount": 2
						}
					]
				}
			],
			"companyName": "Dr Martens",
			"formattedQuestionCount": "44",
			"questionCount": 44,
			"topicFilter": {
				"faqListUrl": "/cmp/Dr-Martens/faq",
				"topics": [
					{
						"displayName": "Hiring Process",
						"id": "HIRED_STEPS",
						"seourl": "hiring-process"
					},
					{
						"displayName": "Benefits",
						"id": "COMP_BENEFITS",
						"seourl": "benefits"
					},
					{
						"displayName": "Interviews",
						"id": "INTERVIEW",
						"seourl": "interviews"
					},
					{
						"displayName": "Working Environment",
						"id": "WORK_ENV",
						"seourl": "working-environment"
					},
					{
						"displayName": "Promotion",
						"id": "RAISE",
						"seourl": "promotion"
					},
					{
						"displayName": "CEO",
						"id": "CEO",
						"seourl": "ceo"
					},
					{
						"displayName": "Drug Test",
						"id": "DRUG_TEST",
						"seourl": "drug-test"
					},
					{
						"displayName": "Working Culture",
						"id": "WORK_CULTURE",
						"seourl": "working-culture"
					},
					{
						"displayName": "Work from Home",
						"id": "WORK_FROM_HOME",
						"seourl": "work-from-home"
					},
					{
						"displayName": "Attire",
						"id": "ATTIRE",
						"seourl": "attire"
					},
					{
						"displayName": "Company Future",
						"id": "COMP_FUTURE",
						"seourl": "company-future"
					},
					{
						"displayName": "Health benefits",
						"id": "HEALTH",
						"seourl": "health-benefits"
					},
					{
						"displayName": "Life insurance",
						"id": "LIFE_INSURANCE",
						"seourl": "life-insurance"
					},
					{
						"displayName": "Salaries",
						"id": "SALARY",
						"seourl": "salary"
					},
					{
						"displayName": "Working Hours",
						"id": "WORK_HOURS",
						"seourl": "working-hours"
					}
				]
			}
		},
		"requestContext": {
			"country": "US",
			"domain": "https://www.indeed.com",
			"locale": "en-US",
			"logUiTimings": false,
			"logWebVitals": false,
			"loggedIn": false,
			"mobileUserAgent": false,
			"rtl": false,
			"throwI18nErrorActive": false,
			"tk": "1h6p80q87iol1802",
			"reactProctor": {
				"tests": {
					"acme_career_services_interview_topic_tab_tst": 2,
					"acme_career_services_interviews_tab_tst": -1,
					"acme_career_services_jobs_tab_tst": 2,
					"acme_cmp_linkback_to_salaries_tst": 1,
					"acme_comp_fullstory_unmask_tog": 1,
					"acme_compui_acronym_search_tst": 1,
					"acme_compui_gg_for_jobs_tst": 1,
					"acme_compui_gg_for_jobs_v2_tst": 0,
					"acme_compui_job_clicks_tst": 1,
					"acme_compui_react_hydrate_root": -1,
					"acme_compui_reviews_login_gate_tst": 1,
					"acme_compui_salary_gg_for_jobs_tst": 1,
					"acme_hackathon_translate_review": 1,
					"acme_happiness_module_snapshot_tst": 3,
					"acme_review_search_tst": 1,
					"acme_sal_calc_toggle": 1,
					"acme_salaries_job_cards_tst": 1,
					"acme_salaries_login_wall_for_g4j_users_tst": 2,
					"acme_salaries_show_estimated_salary_tst": 1,
					"acme_salaries_vision_tst": -1,
					"acme_salary_show_pay_period_selector_tst": 1,
					"acme_show_ihp_apply_button_text_tst": 1,
					"acme_snapshot_jobtitle_pages_tst": 1,
					"acme_top_companies_industry_tst": 1,
					"acme_unverified_strings": 1,
					"talent_brand_custom_content_rich_text_tog": 1,
					"talent_brand_external_user_migration_tst": -1
				}
			},
			"language": "en",
			"ctk": "1h6p80n2jimgp800",
			"url": "/cmp/Dr-Martens",
			"stagingLevel": "prod"
		},
		"reviewRatingOverallSectionViewModel": {
			"overallRating": {
				"ratings": [
					{
						"rating": 3,
						"year": 2023
					},
					{
						"rating": 4.199999809265137,
						"year": 2022
					},
					{
						"rating": 4.25,
						"year": 2021
					},
					{
						"rating": 4.75,
						"year": 2020
					},
					{
						"rating": 3.8888888359069824,
						"year": 2019
					}
				],
				"reviewNote": {
					"totalReviews": "165"
				}
			},
			"reviewCategories": {
				"compensationBenefits": 3.8,
				"culture": 4,
				"jobSecurityAdvancement": 3.3,
				"management": 3.5,
				"workLifeBalance": 3.8
			}
		},
		"reviewsSectionViewModel": {
			"reviews": [
				{
					"currentEmployee": false,
					"jobTitle": "Store Manager",
					"location": "Los Angeles, CA",
					"overallRating": 3,
					"reviewUrl": "/cmp/Dr-Martens/reviews/changes?id=bda5e1a9a3b48ffa",
					"submissionDate": "April 11, 2023",
					"text": "A lot has changed over the years. Upper management styles, brand focus, etc. and it’s definitely made it’s way down to stores. Don’t get me wrong, it all depends on your team and what store you’re in. But as the review further down said…if you’re not favorited, you’re definitely stuck where you are or on your way out. There’s been a lot of external hires in our region, which has definitely been disappointing to see as we have a lot of team members who have been around for YEARS. We got decent raises last year, but at this point the money isn’t worth the stress we’re put under. The boots are great at first, but this company isn’t sustainable for most. I highly suggest to work here as an associate though, if you’re in a chill store. Other downfall is the severe lack of holiday pay. Only Christmas & Juneteenth.",
					"title": "Changes"
				},
				{
					"currentEmployee": true,
					"jobTitle": "Sales Advisor",
					"location": "New York, NY",
					"overallRating": 2,
					"reviewUrl": "/cmp/Dr-Martens/reviews/it-was-really-nice-at-first?id=80a1925df46ca7f5",
					"submissionDate": "May 31, 2023",
					"text": "The job is easy, the customers are chill. Just try your best to make your goal & build customer relations. It’s more of a sales job than retail because you need to actively convince the customers to buy the shoes and upsell products. No commission and they cut hours like crazy. You’ll need a second job unless you’re a student. There’s no dress code, the only requirement is that you wear a pair of docs which they let you pick out. \nUpdate: I have no idea what happened but this is no longer the fun chill company I used to work for. Their rules have gotten increasingly restrictive, and they do not listen to the concerns of any employees below management level. There is no more upward mobility. This company would rather hire outside just to have the more experienced employees train somebody that’s getting paid more than them. Employees are kept in the dark about how sales goals are determined, which makes it hard to reach their targets when they’re scheduled for 4 hour shifts only 2 days a week. There’s so much more I can say… somewhere along the lines the company’s culture definitely changed.",
					"title": "It was really nice at first…"
				},
				{
					"currentEmployee": true,
					"jobTitle": "Store Manager",
					"location": "Frisco, TX",
					"overallRating": 1,
					"reviewUrl": "/cmp/Dr-Martens/reviews/one-of-the-worst-jobs-i-have-ever-worked-for?id=7a1d77f996201b5c",
					"submissionDate": "May 25, 2023",
					"text": "What is the best part of working at the company?\nFree shoes when you are hired. \n\nWhat is the most stressful part about working at the company?\nThe company is very disorganized, to many platforms. A lot of multiple calls to attend that repeat the same pointless information. \n\nWhat is the work environment and culture like at the company?\nThey come off very nice and willing to get to know you and act like they care for your needs and wants. But they are fake and not inclusive. \n\nWhat is a typical day like for you at the company?\nStressful. Lots of back office work.",
					"title": "One of the worst jobs I have ever worked for. "
				},
				{
					"currentEmployee": false,
					"jobTitle": "Sales Assistant",
					"location": "Edinburgh",
					"overallRating": 1,
					"reviewUrl": "/cmp/Dr-Martens/reviews/disrespectful-manager?id=0bf5f6ab2f1d74f1",
					"submissionDate": "May 20, 2023",
					"text": "Worked as seasonal staff and found that one manager in particular nobody liked, and came to understand as to why. This manager was very monotone and did not create a positive work environment, I constantly felt uneasy and any mistake that I made was blown out of proportion - and considering I was only a temp with very little training this to me felt unjust. ",
					"title": "Disrespectful manager"
				},
				{
					"currentEmployee": false,
					"jobTitle": "Warehouse Associate",
					"location": "Portland, OR",
					"overallRating": 2,
					"reviewUrl": "/cmp/Dr-Martens/reviews/left-alone-for-the-most-part?id=2d6bd64061ee7d98",
					"submissionDate": "May 9, 2023",
					"text": " poor management that would rather continue hiring cheap workers and training and retraining them rather than put the effort in to have a more quality work force. ",
					"title": "Left alone for the most part"
				}
			]
		},
		"salarySectionViewModel": {
			"categories": [
				{
					"categoryTitle": "Popular Roles",
					"salaries": [
						{
							"salary": "$21.09",
							"salaryType": "HOURLY",
							"title": "Sales Manager"
						},
						{
							"salary": "$17.10",
							"salaryType": "HOURLY",
							"title": "Sales Associate"
						},
						{
							"salary": "$67,404",
							"salaryType": "YEARLY",
							"title": "Store Manager"
						}
					]
				},
				{
					"categoryTitle": "Retail",
					"salaries": [
						{
							"salary": "$22.35",
							"salaryType": "HOURLY",
							"title": "Stock Supervisor"
						},
						{
							"salary": "$13.08",
							"salaryType": "HOURLY",
							"title": "Retail Sales Associate"
						}
					]
				}
			],
			"count": "591"
		},
		"sectionCount": 13,
		"similarCompaniesSectionViewModel": {
			"similarCompanyCards": [
				{
					"companyLogoUrl": "https://d2q79iu7y748jz.cloudfront.net/s/_squarelogo/64x64/4e24ff1dffc4b9547cc0aa1d931af2db",
					"companyLogoUrl2x": "https://d2q79iu7y748jz.cloudfront.net/s/_squarelogo/128x128/4e24ff1dffc4b9547cc0aa1d931af2db",
					"companyName": "Vans",
					"companyUrl": "/cmp/Vans",
					"compareCompanyUrl": "/companies/compare/Dr-Martens-vs-Vans-4ff833445a13c03b-9b7ffa545b71101f",
					"jobCount": 1249,
					"rating": 4.1,
					"reviewCount": 2382,
					"sectors": [
						"Retail & Wholesale"
					]
				},
				{
					"companyLogoUrl": "https://d2q79iu7y748jz.cloudfront.net/s/_squarelogo/64x64/d3b3437d4c930bfeb11cd4969a1a681e",
					"companyLogoUrl2x": "https://d2q79iu7y748jz.cloudfront.net/s/_squarelogo/128x128/d3b3437d4c930bfeb11cd4969a1a681e",
					"companyName": "Urban Outfitters",
					"companyUrl": "/cmp/Urban-Outfitters-7e13a49d",
					"compareCompanyUrl": "/companies/compare/Dr-Martens-vs-Urban-Outfitters-7e13a49d-4ff833445a13c03b-82d17fc4875dec86",
					"jobCount": 183,
					"rating": 3.5,
					"reviewCount": 2208,
					"sectors": [
						"Retail & Wholesale"
					]
				},
				{
					"companyLogoUrl": "https://d2q79iu7y748jz.cloudfront.net/s/_squarelogo/64x64/19938a990766765355ea3d56028a9da7",
					"companyLogoUrl2x": "https://d2q79iu7y748jz.cloudfront.net/s/_squarelogo/128x128/19938a990766765355ea3d56028a9da7",
					"companyName": "UNIQLO",
					"companyUrl": "/cmp/Uniqlo",
					"compareCompanyUrl": "/companies/compare/Dr-Martens-vs-Uniqlo-4ff833445a13c03b-85a8dec5df8fe966",
					"jobCount": 189,
					"rating": 3.3,
					"reviewCount": 2201,
					"sectors": [
						"Retail & Wholesale"
					]
				},
				{
					"companyLogoUrl": "https://d2q79iu7y748jz.cloudfront.net/s/_squarelogo/64x64/0ae9cfd13d69e36ddb04ffc1aa506983",
					"companyLogoUrl2x": "https://d2q79iu7y748jz.cloudfront.net/s/_squarelogo/128x128/0ae9cfd13d69e36ddb04ffc1aa506983",
					"companyName": "The Cotton On Group",
					"companyUrl": "/cmp/The-Cotton-On-Group",
					"compareCompanyUrl": "/companies/compare/Dr-Martens-vs-The-Cotton-On-Group-4ff833445a13c03b-2d41950b2e5be08e",
					"jobCount": 194,
					"rating": 3.6,
					"reviewCount": 1595,
					"sectors": [
						"Retail & Wholesale"
					]
				},
				{
					"companyLogoUrl": "https://d2q79iu7y748jz.cloudfront.net/s/_squarelogo/64x64/5f1f2cd40c9099c5de91cdb822cde394",
					"companyLogoUrl2x": "https://d2q79iu7y748jz.cloudfront.net/s/_squarelogo/128x128/5f1f2cd40c9099c5de91cdb822cde394",
					"companyName": "Abercrombie & Fitch",
					"companyUrl": "/cmp/Abercrombie-&-Fitch",
					"compareCompanyUrl": "/companies/compare/Dr-Martens-vs-Abercrombie-&-Fitch-4ff833445a13c03b-be498abed75ca2f1",
					"jobCount": 735,
					"rating": 3.5,
					"reviewCount": 5262,
					"sectors": [
						"Retail & Wholesale"
					]
				},
				{
					"companyLogoUrl": "https://d2q79iu7y748jz.cloudfront.net/s/_squarelogo/64x64/9a79303b740518538619198c151e0366",
					"companyLogoUrl2x": "https://d2q79iu7y748jz.cloudfront.net/s/_squarelogo/128x128/9a79303b740518538619198c151e0366",
					"companyName": "PacSun",
					"companyUrl": "/cmp/Pacsun",
					"compareCompanyUrl": "/companies/compare/Dr-Martens-vs-Pacsun-4ff833445a13c03b-7c3252b8ea748df2",
					"jobCount": 657,
					"rating": 3.6,
					"reviewCount": 2595,
					"sectors": [
						"Retail & Wholesale"
					]
				},
				{
					"companyLogoUrl": "https://d2q79iu7y748jz.cloudfront.net/s/_squarelogo/64x64/bf62bdba82898353503a570cb606c750",
					"companyLogoUrl2x": "https://d2q79iu7y748jz.cloudfront.net/s/_squarelogo/128x128/bf62bdba82898353503a570cb606c750",
					"companyName": "Lush Cosmetics",
					"companyUrl": "/cmp/Lush-Cosmetics",
					"compareCompanyUrl": "/companies/compare/Dr-Martens-vs-Lush-Cosmetics-4ff833445a13c03b-06afa4fef6fef102",
					"jobCount": 162,
					"rating": 3.9,
					"reviewCount": 2733,
					"sectors": [
						"Retail & Wholesale"
					]
				},
				{
					"companyLogoUrl": "https://d2q79iu7y748jz.cloudfront.net/s/_squarelogo/64x64/feb1df8dbe99e96ab1b84a97aa8babaa",
					"companyLogoUrl2x": "https://d2q79iu7y748jz.cloudfront.net/s/_squarelogo/128x128/feb1df8dbe99e96ab1b84a97aa8babaa",
					"companyName": "Steve Madden",
					"companyUrl": "/cmp/Steve-Madden",
					"compareCompanyUrl": "/companies/compare/Dr-Martens-vs-Steve-Madden-4ff833445a13c03b-05c8511594ddfc87",
					"jobCount": 526,
					"rating": 3.5,
					"reviewCount": 728,
					"sectors": [
						"Retail & Wholesale"
					]
				},
				{
					"companyLogoUrl": "https://d2q79iu7y748jz.cloudfront.net/s/_squarelogo/64x64/252e7f5d4a3744455ce4d5dd5d3e5a8b",
					"companyLogoUrl2x": "https://d2q79iu7y748jz.cloudfront.net/s/_squarelogo/128x128/252e7f5d4a3744455ce4d5dd5d3e5a8b",
					"companyName": "aerie",
					"companyUrl": "/cmp/Aerie",
					"compareCompanyUrl": "/companies/compare/Dr-Martens-vs-Aerie-4ff833445a13c03b-13d27e5d05bc5860",
					"jobCount": 15,
					"rating": 3.7,
					"reviewCount": 246,
					"sectors": [
						"Retail & Wholesale"
					]
				},
				{
					"companyLogoUrl": "https://d2q79iu7y748jz.cloudfront.net/s/_squarelogo/64x64/f5006b2e62ec61f95fc3c3faa29868d7",
					"companyLogoUrl2x": "https://d2q79iu7y748jz.cloudfront.net/s/_squarelogo/128x128/f5006b2e62ec61f95fc3c3faa29868d7",
					"companyName": "Free People",
					"companyUrl": "/cmp/Free-People",
					"compareCompanyUrl": "/companies/compare/Dr-Martens-vs-Free-People-4ff833445a13c03b-b861e5bf1cf04885",
					"jobCount": 152,
					"rating": 3.8,
					"reviewCount": 232,
					"sectors": [
						"Retail & Wholesale"
					]
				},
				{
					"companyLogoUrl": "https://d2q79iu7y748jz.cloudfront.net/s/_squarelogo/64x64/1815ac150cc4c9ce442cf47718544a71",
					"companyLogoUrl2x": "https://d2q79iu7y748jz.cloudfront.net/s/_squarelogo/128x128/1815ac150cc4c9ce442cf47718544a71",
					"companyName": "Levi Strauss",
					"companyUrl": "/cmp/Levi-Strauss-e85ee6e2",
					"compareCompanyUrl": "/companies/compare/Dr-Martens-vs-Levi-Strauss-e85ee6e2-4ff833445a13c03b-eb660ca38a3d9bf7",
					"jobCount": 518,
					"rating": 3.9,
					"reviewCount": 3195,
					"sectors": [
						"Retail & Wholesale"
					]
				},
				{
					"companyLogoUrl": "https://d2q79iu7y748jz.cloudfront.net/s/_squarelogo/64x64/e639b2c3fd0462de0e26c31206468249",
					"companyLogoUrl2x": "https://d2q79iu7y748jz.cloudfront.net/s/_squarelogo/128x128/e639b2c3fd0462de0e26c31206468249",
					"companyName": "The North Face",
					"companyUrl": "/cmp/The-North-Face",
					"compareCompanyUrl": "/companies/compare/Dr-Martens-vs-The-North-Face-4ff833445a13c03b-77d19f1c62d6380b",
					"jobCount": 340,
					"rating": 4,
					"reviewCount": 680,
					"sectors": [
						"Manufacturing"
					]
				},
				{
					"companyLogoUrl": "https://d2q79iu7y748jz.cloudfront.net/s/_squarelogo/64x64/10fe8e5b927acfd18a45e8d2475b4023",
					"companyLogoUrl2x": "https://d2q79iu7y748jz.cloudfront.net/s/_squarelogo/128x128/10fe8e5b927acfd18a45e8d2475b4023",
					"companyName": "ZARA",
					"companyUrl": "/cmp/Zara",
					"compareCompanyUrl": "/companies/compare/Dr-Martens-vs-Zara-4ff833445a13c03b-22d1d9b09ace2200",
					"jobCount": 109,
					"rating": 3.6,
					"reviewCount": 7815,
					"sectors": [
						"Textile & Apparel Manufacturing"
					]
				},
				{
					"companyLogoUrl": "https://d2q79iu7y748jz.cloudfront.net/s/_squarelogo/64x64/b09e341689022a0308ebaf8f8bd23369",
					"companyLogoUrl2x": "https://d2q79iu7y748jz.cloudfront.net/s/_squarelogo/128x128/b09e341689022a0308ebaf8f8bd23369",
					"companyName": "Garage Clothing",
					"companyUrl": "/cmp/Garage-Clothing",
					"compareCompanyUrl": "/companies/compare/Dr-Martens-vs-Garage-Clothing-4ff833445a13c03b-723eb8b73cd9c869",
					"jobCount": 192,
					"rating": 3.4,
					"reviewCount": 391,
					"sectors": [
						"Retail & Wholesale"
					]
				},
				{
					"companyLogoUrl": "https://d2q79iu7y748jz.cloudfront.net/s/_squarelogo/64x64/f9faea98396be829ff98f7bf72c3acb5",
					"companyLogoUrl2x": "https://d2q79iu7y748jz.cloudfront.net/s/_squarelogo/128x128/f9faea98396be829ff98f7bf72c3acb5",
					"companyName": "Brandy Melville",
					"companyUrl": "/cmp/Brandy-Melville",
					"compareCompanyUrl": "/companies/compare/Dr-Martens-vs-Brandy-Melville-4ff833445a13c03b-e2636788ddf19649",
					"jobCount": 0,
					"rating": 3.3,
					"reviewCount": 167,
					"sectors": [
						"Retail & Wholesale"
					]
				},
				{
					"companyLogoUrl": "https://d2q79iu7y748jz.cloudfront.net/s/_squarelogo/64x64/9b9ea5cdbb5c3668c8838be79b85ca00",
					"companyLogoUrl2x": "https://d2q79iu7y748jz.cloudfront.net/s/_squarelogo/128x128/9b9ea5cdbb5c3668c8838be79b85ca00",
					"companyName": "Tillys",
					"companyUrl": "/cmp/Tillys",
					"compareCompanyUrl": "/companies/compare/Dr-Martens-vs-Tillys-4ff833445a13c03b-7859ba5506d11a62",
					"jobCount": 370,
					"rating": 3.5,
					"reviewCount": 1547,
					"sectors": [
						"Retail & Wholesale"
					]
				},
				{
					"companyLogoUrl": "https://d2q79iu7y748jz.cloudfront.net/s/_squarelogo/64x64/e240ef5924e043166207d2b2d7a2f3b0",
					"companyLogoUrl2x": "https://d2q79iu7y748jz.cloudfront.net/s/_squarelogo/128x128/e240ef5924e043166207d2b2d7a2f3b0",
					"companyName": "Anthropologie",
					"companyUrl": "/cmp/Anthropologie",
					"compareCompanyUrl": "/companies/compare/Dr-Martens-vs-Anthropologie-4ff833445a13c03b-3906cf7d32d78561",
					"jobCount": 308,
					"rating": 3.7,
					"reviewCount": 867,
					"sectors": [
						"Retail & Wholesale"
					]
				},
				{
					"companyLogoUrl": "https://d2q79iu7y748jz.cloudfront.net/s/_squarelogo/64x64/0726c3c66e12fde006eeca7650ff75dd",
					"companyLogoUrl2x": "https://d2q79iu7y748jz.cloudfront.net/s/_squarelogo/128x128/0726c3c66e12fde006eeca7650ff75dd",
					"companyName": "Aritzia",
					"companyUrl": "/cmp/Aritzia",
					"compareCompanyUrl": "/companies/compare/Dr-Martens-vs-Aritzia-4ff833445a13c03b-3e98f026873f32d6",
					"jobCount": 204,
					"rating": 3.3,
					"reviewCount": 492,
					"sectors": [
						"Department, Clothing & Shoe Stores"
					]
				},
				{
					"companyLogoUrl": "https://d2q79iu7y748jz.cloudfront.net/s/_squarelogo/64x64/fd19bcbbe2fd5cd66b7c86b743d77c3a",
					"companyLogoUrl2x": "https://d2q79iu7y748jz.cloudfront.net/s/_squarelogo/128x128/fd19bcbbe2fd5cd66b7c86b743d77c3a",
					"companyName": "Forever 21",
					"companyUrl": "/cmp/Forever-21",
					"compareCompanyUrl": "/companies/compare/Dr-Martens-vs-Forever-21-4ff833445a13c03b-8d5d220df748c761",
					"jobCount": 610,
					"rating": 3.3,
					"reviewCount": 8824,
					"sectors": [
						"Retail & Wholesale"
					]
				},
				{
					"companyLogoUrl": "https://d2q79iu7y748jz.cloudfront.net/s/_squarelogo/64x64/f94fc6610f2de49d4a0b3c9ac09bdf35",
					"companyLogoUrl2x": "https://d2q79iu7y748jz.cloudfront.net/s/_squarelogo/128x128/f94fc6610f2de49d4a0b3c9ac09bdf35",
					"companyName": "Journeys",
					"companyUrl": "/cmp/Journeys",
					"compareCompanyUrl": "/companies/compare/Dr-Martens-vs-Journeys-4ff833445a13c03b-6d8e5fb0844dcc83",
					"jobCount": 4172,
					"rating": 3.5,
					"reviewCount": 5092,
					"sectors": [
						"Retail & Wholesale"
					]
				}
			]
		},
		"topicSectionWonderViewModel": {
			"companyName": "Dr Martens",
			"topicCards": [
				{
					"description": "Explore skills and training, pay raises and promotions and management and culture.",
					"title": "Professional development",
					"url": "/cmp/Dr-Martens/topics/professional-development"
				},
				{
					"description": "Explore company values, community, the relevance of the mission and moving on.",
					"title": "Mission and values",
					"url": "/cmp/Dr-Martens/topics/company-mission-and-values"
				},
				{
					"description": "Explore PTO allowances, work-life balance and flexibility and parental leave.",
					"title": "PTO and work-life balance",
					"url": "/cmp/Dr-Martens/topics/pto-work-life-balance"
				},
				{
					"description": "Explore work from home during COVID-19, remote work support and work-life balance.",
					"title": "Work from home",
					"url": "/cmp/Dr-Martens/topics/work-from-home"
				},
				{
					"description": "Explore parental leave policies and other benefits, company culture and general support.",
					"title": "Parents and caregivers",
					"url": "/cmp/Dr-Martens/topics/parents-and-caregivers"
				},
				{
					"description": "Explore support and satisfaction with programs for new and emerging graduates.",
					"title": "Internships and graduate programs",
					"url": "/cmp/Dr-Martens/topics/internships-graduate-programs"
				},
				{
					"description": "Explore leadership during COVID-19, working conditions and WFH support.",
					"title": "COVID-19 response",
					"url": "/cmp/Dr-Martens/topics/covid-19-response"
				},
				{
					"description": "Explore employer support and available accommodations for people with disabilities.",
					"title": "Accessibility, Disability and Accommodation",
					"url": "/cmp/Dr-Martens/topics/accessibility-disability-accommodation"
				}
			]
		}
	},
	"companyWebsite": "https://jobs.drmartens.com/",
	"companyCEOName": "Kenny Wilson, CEO Dr Martens PLC"
}
```


## JSON Data Documentation

This documentation provides an overview and description of the fields present in the given JSON data obtained from indeed.com.

- `company`: The name of the company offering the job.
- `companyBrandingAttributes`: Additional branding attributes of the company.
  - `headerImageUrl`: The URL of the header image associated with the company.
  - `logoUrl`: The URL of the company's logo image.
- `companyOverviewLink`: The URL to the company's overview page.
- `companyRating`: The company's rating on Indeed.
- `companyReviewCount`: The number of reviews for the company.
- `displayTitle`: The displayed title of the job.
- `dradisJob`: A boolean value indicating if it is a DRADIS job.
- `employerAssistEnabled`: A boolean value indicating if employer assist is enabled.
- `employerResponsive`: A boolean value indicating if the employer is responsive.
- `encryptedFccompanyId`: The encrypted ID of the FCC company.
- `expired`: A boolean value indicating if the job posting has expired.
- `extractedSalary`: The extracted salary information.
  - `max`: The maximum salary value.
  - `min`: The minimum salary value.
  - `type`: The type of salary (e.g., yearly, monthly).
- `fccompanyId`: The FCC company ID.
- `featuredCompanyAttributes`: Additional attributes of the featured company.
- `featuredEmployer`: A boolean value indicating if the employer is featured.
- `featuredEmployerCandidate`: A boolean value indicating if the employer is featured for the candidate.
- `feedId`: The ID of the job feed.
- `formattedLocation`: The formatted location of the job.
- `formattedRelativeTime`: The relative time when the job was posted.
- `hideMetaData`: A boolean value indicating if metadata is hidden.
- `highVolumeHiringModel`: The high volume hiring model information.
  - `highVolumeHiring`: A boolean value indicating if high volume hiring is enabled.
- `hiringEventJob`: A boolean value indicating if it is a hiring event job.
- `homepageJobFeedSectionId`: The ID of the job feed section on the homepage.
- `indeedApplyEnabled`: A boolean value indicating if Indeed Apply is enabled.
- `indeedApplyable`: A boolean value indicating if the job is Indeed Applyable.
- `isJobVisited`: A boolean value indicating if the job has been visited.
- `isMobileThirdPartyApplyable`: A boolean value indicating if third-party mobile application is available.
- `isNoResumeJob`: A boolean value indicating if the job does not require a resume.
- `isSubsidiaryJob`: A boolean value indicating if it is a subsidiary job.
- `jobCardRequirementsModel`: The model containing information about job card requirements.
  - `additionalRequirementsCount`: The count of additional job requirements.
  - `requirementsHeaderShown`: A boolean value indicating if the requirements header is shown
- `jobLocationCity`: The city where the job is located.
- `jobLocationState`: The state where the job is located.
- `jobTypes`: An array of job types associated with the job.
- `jobkey`: The key associated with the job.
- `jsiEnabled`: A boolean value indicating if JSI (Job Spotter Integration) is enabled.
- `link`: The URL link to the job posting.
- `locationCount`: The count of locations associated with the job.
- `mobtk`: The mobile token associated with the job.
- `newJob`: A boolean value indicating if it is a new job posting.
- `normTitle`: The normalized title of the job.
- `openInterviewsInterviewsOnTheSpot`: A boolean value indicating if interviews are conducted on the spot for open interviews.
- `openInterviewsJob`: A boolean value indicating if it is an open interviews job.
- `openInterviewsOffersOnTheSpot`: A boolean value indicating if offers are made on the spot for open interviews.
- `openInterviewsPhoneJob`: A boolean value indicating if it is a phone job for open interviews.
- `overrideIndeedApplyText`: A boolean value indicating if the Indeed Apply text is overridden.
- `preciseLocationModel`: The model containing information about the precise location.
  - `obfuscateLocation`: A boolean value indicating if the location should be obfuscated.
  - `overrideJCMPreciseLocationModel`: A boolean value indicating if the JCMPreciseLocationModel is overridden.
- `pubDate`: The publication date of the job posting.
- `rankingScoresModel`: The model containing ranking scores for the job.
  - `bid`: The bid score.
  - `eApply`: The eApply score.
  - `eQualified`: The eQualified score.
- `redirectToThirdPartySite`: A boolean value indicating if the user should be redirected to a third-party site.
- `remoteLocation`: A boolean value indicating if the job is a remote location.
- `remoteWorkModel`: The model containing information about remote work.
  - `inlineText`: A boolean value indicating if the text should be displayed inline.
  - `type`: The type of remote work (e.g., REMOTE_HYBRID).
- `resumeMatch`: A boolean value indicating if the user's resume is a match for the job.
- `salarySnippet`: The snippet of salary information.
  - `currency`: The currency of the salary.
  - `salaryTextFormatted`: A boolean value indicating if the salary text is formatted.
  - `source`: The source of the salary information.
  - `text`: The text of the salary information.
- `screenerQuestionsURL`: The URL for screener questions.
- `showAttainabilityBadge`: A boolean value indicating if the attainability badge should be shown.
- `showCommutePromo`: A boolean value indicating if the commute promotion should be shown.
- `showEarlyApply`: A boolean value indicating if the early apply option should be shown.
- `showJobType`: A boolean value indicating if the job type should be shown.
- `showRelativeDate`: A boolean value indicating if the relative date should be shown.
- `showSponsoredLabel`: A boolean value indicating if the sponsored label should be shown.
- `showStrongerAppliedLabel`: A boolean value indicating if the stronger applied label should be shown.
- `smartFillEnabled`: A boolean value indicating if smart fill is enabled.
- `smbD2iEnabled`: A boolean value indicating if SMB (Small and Medium-sized Business) D2I is enabled.
- `snippet`: The snippet of the job description.
- `sourceId`: The ID of the data source.
- `sponsored`: A boolean value indicating if the job posting is sponsored.
- `taxoAttributes`: The taxonomy attributes associated with the job.
- `taxoAttributesDisplayLimit`: The limit of taxonomy attributes to display.
- `taxoLogAttributes`: The taxonomy log attributes associated with the job.
- `taxonomyAttributes`: The taxonomy attributes associated with the job.
  - `attributes`: The attributes of the taxonomy.
    - `label`: The label of the attribute.
    - `suid`: The SUID (System Unique Identifier) of the attribute.
  - `label`: The label of the taxonomy.
- `tier`: The tier information associated with the job.
  - `matchedPreferences`: The matched preferences within the tier.
    - `longMatchedPreferences`: An array of long matched preferences.
    - `stringMatchedPreferences`: An array of string matched preferences.
  - `type`: The type of the tier.
- `title`: The title of the job.
- `translatedAttributes`: The translated attributes of the job.
- `translatedCmiJobTags`: The translated CMI (Career Management Integration) job tags.
- `truncatedCompany`: The truncated name of the company.
- `urgentlyHiring`: A boolean value indicating if the employer is urgently hiring.
- `viewJobLink`: The link to view the job details.
- `vjFeaturedEmployerCandidate`: A boolean value indicating if the employer is featured for the candidate on VJ (View Job) page.
- `workplaceInsights`: Insights about the workplace associated with the job.

## How much will it cost me to scrape Indeed jobs ?
To use this scraper you need to pay $20 per month fixed cost to the developer and you should have an [Apify subscription](https://apify.com/pricing?fpr=ve081&fp_sid=github_indeed-scraper) which starts from $49/mo prepaid usage credits. 
Based on historical data our scraper costs an average of $0.73 per thousand jobs scraped as usage credits.
Based on above data, you can scrape upto 67,000 jobs per month with starter plan

## Is it legal to scrape indeed.com ?
Our scrapers are ethical and do not extract any private user data, such as email addresses, gender, or location. They only extract what the user has chosen to share publicly. We therefore believe that our scrapers, when used for ethical purposes by Apify users, are safe. 
However, you should be aware that your results could contain personal data. Personal data is protected by the [GDPR](https://docs.apify.com/academy/get-most-of-actors/actor-readme#:~:text=protected%20by%20the-,GDPR,-in%20the%20European?fpr=ve081&fp_sid=github_indeed-scraper) in the European Union and by other regulations around the world. 
You should not scrape personal data unless you have a legitimate reason to do so. If you're unsure whether your reason is legitimate, consult your lawyers. You can also read our blog post on the [legality of web scraping](https://blog.apify.com/is-web-scraping-legal/?fpr=ve081&fp_sid=github_indeed-scraper)

## Your feedback
We’re always working on improving the performance of our Actors. So if you’ve got any technical feedback for Indeed Scraper or simply found a bug, please create an issue on the actor’s [Issues](https://console.apify.com/actors/qA8rz8tR61HdkfTBL/issues?fpr=ve081&fp_sid=github_indeed-scraper) tab in Apify Console.
