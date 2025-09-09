
# Getting Started with FeedbackFlow

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

![Welcome dialog placeholder](https://github.com/user-attachments/assets/0bcd6f65-ac17-4cba-9e59-85be24f9ac28)

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

![Organization management placeholder](./images/organization-management.png)

### Organization Settings

Configure your organization:
- **Name**: Set a descriptive name
- **Logo**: Upload your brand logo
- **Settings**: Configure feedback collection preferences (coming soon)

![Organization settings placeholder](./images/organization-settings.png)

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

![Feedback form card placeholder](./images/feedback-form-card.png)

#### Sharing Options

#### Direct Link Sharing
- Copy the feedback form URL
- Share via email, chat, or embed in your website

#### QR Code Sharing
1. Click the QR code icon in the feedback form card
2. Display the QR code for easy mobile access
3. Download the QR code as an SVG file and share it to your users

![QR code generation placeholder](./images/qr-code-generation.png)

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

![Feedback form interface placeholder](https://github.com/user-attachments/assets/24f4ccd8-3a6a-4219-b974-d398abc0af1c)

### Uploading Feedback via CSV
For bulk feedback uploads, use the CSV upload feature:
1. Navigate to [/reviews](https://feedbackflow.org/reviews)
2. Click "Upload CSV"
3. Follow the instructions to format and upload your CSV file

![CSV upload placeholder](./images/csv-upload.png)

### API Integration
For advanced users, FeedbackFlow offers an API that allows for the submission of feedback programmatically. More details can be found in the [API docs](https://feedbackflow.org/api/docs). Detailed step by step documentaion coming soon. 

## Managing Feedback

### Reviews Dashboard

Navigate to [/reviews](https://feedbackflow.org/reviews) to see all submitted feedback:

![Reviews dashboard placeholder](./images/reviews-dashboard.png)

## Generating Insights

### AI-Powered Analytics

Navigate to [/insights](https://feedbackflow.org/insights) to access AI-generated insights:

![Insights dashboard placeholder](./images/insights-dashboard.png)

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

![Insight generation process placeholder](./images/insight-generation-process.png)


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


![Credit balance placeholder](./images/credit-balance.png)

### Managing Billing

1. Navigate to [/billing](https://feedbackflow.org/billing) to manage your subscription
2. View current usage
3. Purchase additional credits
4. Manage payment methods

![Billing dashboard placeholder](./images/billing-dashboard.png)

## Support & Resources

### Getting Help

Need assistance? We're here to help:

#### Email Support
- **General inquiries**: [oscar@feedbackflow.org](mailto:oscar@feedbackflow.org)

#### Community Support
- **Discord**: [Join our community](https://discord.gg/VGCbvbfq)
- **Bug reports**: [Submit via Notion](https://aritra041999.notion.site/23ff573231ea80dfad0ccbf1a8ae3bce?pvs=105)

![Support channels placeholder](./images/support-channels.png)


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
