Teen Hustle Starter Kit
------------------------

Welcome to your first step in making real money online as a teen (ages 13-17)! This guide will show you how to make your first $100 using just your phone and a little hustle.

------------------------

TOP APPS THAT PAY TEENS

1. InboxDollars - Get paid for surveys, watching videos & more.
2. Mistplay - Play Android games and earn gift cards.
3. Survey Junkie - Quick surveys, fast payouts.
4. Fetch Rewards - Scan receipts, earn rewards.
5. Rakuten - Shop and get cash back.

------------------------

HOW TO USE REFERRAL LINKS

- Sign up for apps that offer bonuses when friends join.
- Post links on your TikTok, IG bio, Snapchat, or in group chats.
- Make a short video showing how the app works.

------------------------

3-DAY ACTION PLAN

DAY 1 - Sign up for 3 apps and start using them.
DAY 2 - Invite 5 friends to each app with your referral link.
DAY 3 - Make a social media post or video showing your results.

------------------------

WHERE TO SHARE LINKS

- IG Bio
- TikTok Stories/Comments
- Linktree or Beacons page
- Group chats and school friends

------------------------

BONUS TIPS

- Always be honest about your experience.
- Use a parent email if required.
- Avoid scams - only use trusted sites.

You've got this! Follow @vaultdistrictsinc for more tips.

- Vault Districts
"""

# Create and export the PDF with cleaned content
pdf = FPDF()
pdf.add_page()
pdf.set_font("Arial", 'B', 16)
pdf.cell(0, 10, "Teen Hustle Starter Kit", ln=True, align='C')

pdf.set_font("Arial", '', 12)
pdf.ln(10)
pdf.multi_cell(0, 10, clean_text)

# Save PDF
output_path = "/mnt/data/Teen_Hustle_Starter_Kit_VaultDistricts.pdf"
pdf.output(output_path)
output_path
