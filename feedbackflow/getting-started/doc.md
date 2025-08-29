# Getting Started with FeedbackFlow

Welcome to FeedbackFlow! 🎉 This comprehensive guide will walk you through everything you need to know to get started with collecting, managing, and analyzing customer feedback.

## What is FeedbackFlow?

FeedbackFlow is a web application designed to streamline the process of collecting and managing customer feedback. It provides a user-friendly interface for customers to submit feedback, while offering powerful tools for administrators to review, analyze, and act on that feedback.

## Table of Contents

1. [Quick Start](#quick-start)
2. [Account Setup](#account-setup)
3. [Setting Up Your Organization](#setting-up-your-organization)
4. [Collecting Feedback](#collecting-feedback)
5. [Managing Feedback](#managing-feedback)
6. [Generating Insights](#generating-insights)
7. [API Integration](#api-integration)
8. [Billing & Credits](#billing--credits)
9. [Advanced Features](#advanced-features)
10. [Support & Resources](#support--resources)

---

## Quick Start

### Step 1: Sign Up & Login

1. Visit [FeedbackFlow](https://feedbackflow.org)
2. Click "Login with Google" to create your account
3. You'll be automatically redirected to your dashboard

### Step 2: Welcome Dialog

Upon your first login, you'll see a welcome dialog with key steps to get started:

![Welcome dialog placeholder](https://github.com/user-attachments/assets/0bcd6f65-ac17-4cba-9e59-85be24f9ac28)

---

## Account Setup

### Initial Setup

When you first sign up, FeedbackFlow automatically:
- Creates your user account
- Sets up a new organization for you
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
- **Settings**: Configure feedback collection preferences

![Organization settings placeholder](./images/organization-settings.png)

---

## Collecting Feedback

### Your Feedback Form

Each organization gets a unique feedback form URL:
```
https://feedbackflow.org/collect/[your-organization-id]
```

### Accessing Your Form Link

1. Go to your **Dashboard**
2. Find the "Your Feedback Form" card
3. Copy the link or generate a QR code

![Feedback form card placeholder](./images/feedback-form-card.png)

### Sharing Options

#### Direct Link Sharing
- Copy the feedback form URL
- Share via email, chat, or embed in your website

#### QR Code Sharing
1. Click the QR code icon in the feedback form card
2. Display the QR code for easy mobile access
3. Download the QR code as an SVG file

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

### Feedback Form Features

Your customers can:
- Submit text feedback
- Rate their experience
- Provide contact information (optional)
- Upload attachments (if enabled)

![Feedback form interface placeholder](https://github.com/user-attachments/assets/24f4ccd8-3a6a-4219-b974-d398abc0af1c)



---

## Managing Feedback

### Reviews Dashboard

Navigate to **/reviews** to see all submitted feedback:

![Reviews dashboard placeholder](./images/reviews-dashboard.png)

### Feedback Management Features

#### Viewing Feedback
- See all feedback in chronological order
- Filter by rating, date, or keywords
- Search through feedback content

#### Responding to Feedback
1. Click on any feedback item
2. Add internal notes
3. Mark as resolved or needs follow-up

![Feedback detail view placeholder](./images/feedback-detail-view.png)

#### Organizing Feedback
- Tag feedback by category
- Assign to team members
- Set priority levels

### Bulk Operations

Select multiple feedback items to:
- Mark as resolved
- Apply tags
- Export for external analysis

![Bulk operations placeholder](./images/bulk-operations.png)

---

## Generating Insights

### AI-Powered Analytics

Navigate to **/insights** to access AI-generated insights:

![Insights dashboard placeholder](./images/insights-dashboard.png)

### Available Insights

#### Sentiment Analysis
- Overall sentiment trends
- Positive/negative feedback ratios
- Sentiment over time

#### Topic Extraction
- Common themes and topics
- Trending issues
- Feature requests

#### Action Items
- AI-generated action items based on feedback
- Priority recommendations
- Implementation suggestions

### Generating New Insights

1. Go to the **Insights** page
2. Select the time period for analysis
3. Click "Generate Insights"
4. Review AI-generated recommendations

![Insight generation process placeholder](./images/insight-generation-process.png)

### Action Items

Access **/action-items** to see AI-generated recommendations:

![Action items dashboard placeholder](./images/action-items-dashboard.png)

---

## API Integration

### API Overview

FeedbackFlow provides a RESTful API for programmatic access to your feedback data.

### Authentication

All API requests require authentication. Generate API keys in **/keys**:

![API keys management placeholder](./images/api-keys-management.png)

### Ingest Endpoint

Submit feedback programmatically using the ingest API:

```bash
curl -X POST https://feedbackflow.org/api/ingest \
  -H "Authorization: Bearer YOUR_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{
    "feedback": "Great product, but needs better documentation",
    "rating": 4,
    "email": "customer@example.com",
    "metadata": {
      "source": "mobile_app",
      "version": "1.2.3"
    }
  }'
```

### Available Endpoints

- `POST /api/ingest` - Submit feedback
- `GET /api/reviews` - Retrieve feedback
- `GET /api/insights` - Get generated insights
- `GET /api/analytics` - Access analytics data

### API Documentation

Access full API documentation at **/docs/api** (coming soon).

![API documentation placeholder](./images/api-documentation.png)

---

## Billing & Credits

### Credit System

FeedbackFlow uses a credit-based system:
- Each feedback submission costs 1 credit
- AI insight generation costs 5 credits
- View current balance in the sidebar

![Credit balance placeholder](./images/credit-balance.png)

### Managing Billing

1. Navigate to **/billing**
2. View current usage
3. Purchase additional credits
4. Manage payment methods

![Billing dashboard placeholder](./images/billing-dashboard.png)

### Pricing Plans

Choose from various credit packages:
- Starter: 100 credits
- Growth: 500 credits
- Enterprise: Custom pricing

![Pricing plans placeholder](./images/pricing-plans.png)

---

## Advanced Features

### Integrations

Connect FeedbackFlow with your existing tools:

![Integrations page placeholder](./images/integrations-page.png)

#### Available Integrations
- Slack notifications
- Email alerts
- Webhook endpoints
- Zapier automation

### Custom Questions

Create custom feedback forms with specific questions:

1. Go to **/questions**
2. Design your custom form
3. Deploy to your feedback URL

![Custom questions setup placeholder](./images/custom-questions-setup.png)

### Form Customization

Customize your feedback form:
- Brand colors and logo
- Custom questions
- Required fields
- Thank you messages

![Form customization placeholder](./images/form-customization.png)

### Analytics Dashboard

Access detailed analytics at **/dashboard**:

![Analytics dashboard placeholder](./images/analytics-dashboard.png)

#### Available Metrics
- Feedback volume over time
- Sentiment trends
- Response rates
- User engagement

---

## Support & Resources

### Getting Help

Need assistance? We're here to help:

#### Email Support
- **General inquiries**: [aritra@feedbackflow.org](mailto:aritra@feedbackflow.org)
- **Technical support**: Available via dashboard

#### Community Support
- **Discord**: [Join our community](https://discord.gg/VGCbvbfq)
- **Bug reports**: [Submit via Notion](https://aritra041999.notion.site/23ff573231ea80dfad0ccbf1a8ae3bce?pvs=105)

![Support channels placeholder](./images/support-channels.png)

### Documentation

- **API Reference**: Coming soon
- **Video Tutorials**: Available on our YouTube channel
- **Blog**: Best practices and tips

### Roadmap

Stay updated with upcoming features at **/roadmap**.

![Product roadmap placeholder](./images/product-roadmap.png)

### Feedback on FeedbackFlow

We use our own product! Share your thoughts:
- [Give us feedback](https://feedbackflow.org/collect/226618c4-6e5c-43f1-9688-a9c4437a8900)
- Vote on feature requests
- Join beta testing programs

---

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

---

## Troubleshooting

### Common Issues

#### Feedback Form Not Loading
- Check your organization ID in the URL
- Ensure your organization is active
- Contact support if issues persist

#### API Authentication Errors
- Verify your API key is correct
- Check that the key hasn't expired
- Ensure proper headers are included

#### Credit Balance Issues
- Check your current credit balance
- Purchase additional credits if needed
- Review your usage in the billing section

### Need More Help?

If you can't find what you're looking for:
- Check our [FAQ section](./faq) (coming soon)
- Email us at [aritra@feedbackflow.org](mailto:aritra@feedbackflow.org)
- Join our [Discord community](https://discord.gg/VGCbvbfq)

---

*Welcome to FeedbackFlow! We're excited to help you make sense of your customer feedback. Remember, we're in public beta and constantly improving based on what you tell us.* 🚀
