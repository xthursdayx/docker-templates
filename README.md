# Unraid Templates

unRAID Docker templates for Docker images in the "xthursdayx" repository.

## Usage

All templates are avaialble through the [Community Applications](https://raw.githubusercontent.com/Squidly271/community.applications/master/plugins/community.applications.plg
) plugin on unRAID.

This guide is written for Unraid ver 6.8.3 or later, once installed follow the instructions below:

1. Navigate to ***Docker*** tab and then the ***Docker Repositories*** sub-tab in the unRAID WebUI.
2. Enter the URL https://github.com/xthursdayx/docker-templates in the ***Template repositories*** field.
3. Click on the ***Save*** button.
4. Click back to the ***Docker*** tab and then click on the ***Add Container*** button.
5. Click on the ***Template*** dropdown menu and select the desired Docker image template (e.g. gPodder, Coturn, etc).
6. Toggle the ***Advanced View*** option on the top right of the WebUI and fill in required fields, e.g. volume mapings, environment variables, etc.
7. Click on the ***Create*** button at the bottom of the window to pull the Docker image.
8. Once the image is downloaded you should see it appear on your Docker page.

## Forums

For more information check out my [Unraid template Forum](https://forums.unraid.net/topic/88410-support-xthursdayx-unraid-docker-templates/) for these templates.

## Base XML Template

```xml
<?xml version="1.0" encoding="utf-8"?>
<Container version="2">
  <Beta>True</Beta>
  <Category></Category>
  <Date></Date>
  <TemplateURL/>
  <Icon/>
  <Name></Name>
  <Repository></Repository>
  <Registry></Registry>
  <Support></Support>
  <Project></Project>
  <Overview></Overview>
  <DonateText/>
  <DonateLink/>
  <WebUI></WebUI>
  <Network>bridge</Network>
  <Shell>sh</Shell>
  <Privileged>false</Privileged>
  <ExtraParams/>
  <PostArgs/>
  <DonateImg/>
  <BaseImage/>
  <Branch/>
  <License/>
  <GitHub/>
  <BindTime/>
  <Banner/>
  <Version/>
</Container>
```

## Donate

If you appreciate my work please consider buying me a coffee, cheers! 😁

<a href="https://www.buymeacoffee.com/xthursdayx" rel="external nofollow"><img src="https://www.paypal.com/en_US/i/btn/btn_donate_SM.gif" alt="Donate" width="74"/></a>  
