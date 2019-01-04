This CV is not just a CV, it's an open source web app that:
- Uses Azure
  - The app runs [in the Azure App Service](cv.tomhigson.com)
  - The CV content is stored in Azure blob storage, accessed using a data service
  - Both the app and the content are automatic deployed to staging areas whenever they are updated using Azure DevOps
  - Metrics are tracked and reported using Azure Application Insights
  - The app is secured using SSL certificates stored in the Azure key vault
- Leverages properly formatted Angular structuring to allow component reuse
- Is reactive to different display sizes and types
- Provides print appropriate formatting using media queries
- (coming soon) is service worker ready

As my work is typically security controlled and so cannot be shared, I hope this CV helps demonstrate some of my technical abilities. Check out [the repository](https://github.com/TomHigson/CV) for more details