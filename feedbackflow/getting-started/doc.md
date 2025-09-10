
Welcome to FeedbackFlow! 🎉 This comprehensive guide will walk you through everything you need to know to get started with collecting, managing, and analyzing customer feedback.

## What is FeedbackFlow?

FeedbackFlow is a web application designed to streamline the process of collecting and managing customer feedback. It provides a user-friendly interface for customers to submit feedback, while offering powerful tools for administrators to review, analyze, and act on that feedback.

## Quick Start

### Step 1: Sign Up & Login

1. Visit [FeedbackFlow](https://feedbackflow.org)
2. Click "Login with Google" to create your account
3. You'll be automatically redirected to your dashboard

### Step 2: Welcome Dialog

Upon your first login, you'll see a welcome dialog with key steps to get started:

![Welcome dialog placeholder](https://github.com/user-attachments/assets/249c95ce-d6b3-4834-b752-f0891a55d531)
## Account Setup

### Initial Setup

When you first sign up, FeedbackFlow automatically:
- Creates your user account
- Sets up a new organization with 100 free credits for you so that you can generate insights and action items
- Redirects you to the dashboard with a welcome guide

## Setting Up Your Organization

### Understanding Organizations

Organizations in FeedbackFlow allow you to:
- Separate feedback for different products/teams
- Manage access and permissions
- Track usage and billing separately

### Managing Organizations

1. Click on your organization name in the sidebar
2. Select "Manage Organizations" from the dropdown
3. Create additional organizations or modify existing ones

![Organization management placeholder](https://github.com/user-attachments/assets/6ee15083-8a67-4244-8df5-7043cdf41912)

### Organization Settings

Configure your organization:
- **Name**: Set a descriptive name
- **Logo**: Upload your brand logo
- **Settings**: Configure feedback collection preferences (coming soon)

![Organization settings placeholder](https://github.com/user-attachments/assets/05a1ebbb-0b55-41c3-ae93-9f07da29989e)

## Collecting Feedback

### Your Feedback Form

Each organization gets a unique feedback form URL:
```
https://feedbackflow.org/collect/[your-organization-id]
```

#### Accessing Your Form Link

1. Go to your **Dashboard**
2. Find the "Your Feedback Form" card
3. Share the link or the QR code to collect feedback from your users. 

![Feedback form card placeholder](https://github.com/user-attachments/assets/3c7e8ce9-0e86-49e8-a824-e81c68f3c7a0)

#### Sharing Options

#### Direct Link Sharing
- Copy the feedback form URL
- Share via email, chat, or embed in your website

#### QR Code Sharing
1. Click the QR code icon in the feedback form card
2. Display the QR code for easy mobile access
3. Download the QR code as an SVG file and share it with your users

#### Website Integration
Embed the feedback form directly into your website:

```html
<iframe 
  src="https://feedbackflow.org/collect/[your-organization-id]" 
  width="100%" 
  height="500px"
  frameborder="0">
</iframe>
```

#### Feedback Form Features

Your customers / users can:
- Submit text feedback
- Rate their experience

![Feedback form interface placeholder](https://github.com/user-attachments/assets/6d2b3c84-8444-4777-a17c-8ddf4b59d870)

### Uploading Feedback via CSV
For bulk feedback uploads, use the CSV upload feature:
1. Navigate to [/reviews](https://feedbackflow.org/reviews)
2. Click "Upload CSV"
3. Follow the instructions to format and upload your CSV file

![CSV upload placeholder](https://github.com/user-attachments/assets/6f7c8e29-34d1-4cfe-974b-67ed90920957)
![CSV upload verify](https://github.com/user-attachments/assets/074cddae-ba28-4ea8-bf8b-0cdb282fbd41)


### API Integration
For advanced users, FeedbackFlow offers an API that allows for the submission of feedback programmatically. More details can be found in the [API docs](https://feedbackflow.org/api/docs). Detailed step by step documentaion coming soon. 

![API Docs](https://github.com/user-attachments/assets/36e29f8d-6eb0-47ad-bfbf-693ce7fb1376)

## Managing Feedback

### Reviews Dashboard

Navigate to [/reviews](https://feedbackflow.org/reviews) to see all submitted feedback:

![Reviews dashboard placeholder](https://github.com/user-attachments/assets/6daa8b36-1c12-4090-b948-c94ad37ce530)

## Generating Insights

### AI-Powered Analytics

Navigate to [/insights](https://feedbackflow.org/insights) to access AI-generated insights:

![Insights dashboard placeholder](https://github.com/user-attachments/assets/205f9a9f-1060-40c4-b617-28efae5378b9)

### Available Insights

#### Sentiment Analysis
- Overall sentiment trends
- Positive/negative feedback ratios

#### Insights Summary
- Key themes and topics
- Common pain points
- Frequently requested features

#### Action Items
- AI-generated action items based on feedback
- Priority recommendations
- Implementation suggestions

### Generating New Insights

1. Go to the [/insights](https://feedbackflow.org/insights) page
3. Click "Generate Insights"
4. Review AI-generated recommendations

## Billing & Credits

### Credit System

FeedbackFlow uses a credit-based system:
- Each organization starts with 100 free credits
- Credits are used for generating AI insights and action items
- View current balance in the sidebar
- AI insight generation costs credits based on the volume of feedback processed

| Number of Feebacks | Credit required |
| --- | --- |
| Less than 100 | 35 |
| 100 - 1000 | 45 |
| More than 1000 | 60 |

### Managing Billing

1. Navigate to [/billing](https://feedbackflow.org/billing) to manage your subscription
2. View current usage
3. Purchase additional credits
4. Manage payment methods

![Billing dashboard placeholder](https://github.com/user-attachments/assets/06383783-78fd-4e89-be52-a4f79d1167f5)

## Support & Resources

### Getting Help

Need assistance? We're here to help:

#### Email Support
- **General inquiries**: [oscar@feedbackflow.org](mailto:oscar@feedbackflow.org)

#### Community Support
- **Discord**: [Join our community](https://discord.gg/VGCbvbfq)
- **Bug reports**: [Submit via Notion](https://aritra041999.notion.site/23ff573231ea80dfad0ccbf1a8ae3bce?pvs=105)


#### Feedback & Feature Requests

We use our own product! Share your thoughts:
- [Give us feedback](https://feedbackflow.org/collect/226618c4-6e5c-43f1-9688-a9c4437a8900)
- Vote on feature requests
- Join beta testing programs

## Next Steps

Now that you're set up with FeedbackFlow:

1. ✅ **Share your feedback form** with customers
2. ✅ **Import existing feedback** using the API
3. ✅ **Review incoming feedback** on the reviews page
4. ✅ **Generate your first insights** using AI
5. ✅ **Set up integrations** to streamline your workflow

### Quick Actions

- [📊 View Dashboard](./dashboard)
- [📝 Check Reviews](./reviews)
- [🧠 Generate Insights](./insights)
- [⚙️ Manage Settings](./settings)
- [💳 Billing & Credits](./billing)


*Welcome to FeedbackFlow! We're excited to help you make sense of your customer feedback. Remember, we're in public beta and constantly improving based on what you tell us.* 🚀
