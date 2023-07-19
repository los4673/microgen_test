---
blocks:
  - style:
      alignment: 'flex-col-reverse items-center '
      padding: 'pt-64 pb-64 pr-10 pl-10 sm:pt-28 sm:pb-28 sm:pr-5 sm:pl-5'
      featureImage: '  mx-auto'
      featureContent: 'w-2/3 min-h-0 text-center sm:w-full sm:min-h-0 sm:text-center'
      buttonsLayout: 'flex-wrap  '
      labelStyles: 'text-white mg-headline-small '
      headlineStyles: 'text-white mg-headline-large '
      subheadStyles: 'text-white mg-copy-large '
      textStyles: 'text-white mg-copy '
    background:
      fillStyles: ' opacity-100'
      wrapFillStyles: ' opacity-100'
      src: /uploads/DesertBackground.jpeg
      style: bg-cover
      position: bg-center
    label: ''
    headline: MNBlockchain Test Site
    subhead: ''
    body: >
      Quickly build mobile-friendly websites with an intuitive, easy-to-use
      visual editor and customizable components. Execute your exact design
      vision with the flexible theme editor and background system. Add your own
      components, extend the project however you like, and host it anywhere.
    buttons:
      - label: Get Started
        link: 'https://github.com/MicrogenSite/microgen'
        icon: arrow-right-solid
        buttonStyle: primary
        fathomId: ''
    _template: feature
  - style:
      alignment: 'flex-col-reverse items-center '
      padding: pt-0 pb-0.5 pr-0 pl-0
      featureContent: w-full min-h-0 text-center
      buttonsLayout: 'flex-row  '
      labelStyles: text-white undefined undefined
      headlineStyles: text-white mg-hidden undefined
      subheadStyles: text-white undefined undefined
      textStyles: text-white undefined undefined
    cardStyle:
      fillStyles: bg-black opacity-100
      grid: >-
        grid-cols-3 justify-start gap-0.5 sm:grid-cols-1 sm:justify-start
        sm:gap-0.5
      alignment: flex-col items-start  text-left
      image: wpx-48 hpx-48 object-left object-fill
      imagePadding: 'pt-20 pb-0 pr-0 pl-10 sm:pt-10 sm:pb-0 sm:pr-0 sm:pl-5'
      contentPadding: 'pt-5 pb-12 pr-11 pl-11 sm:pt-5 sm:pb-2.5 sm:pr-5 sm:pl-5'
      borderStyles: border-white border-0
      labelStyles: text-white undefined undefined
      headlineStyles: text-white mg-headline-small undefined
      subheadStyles: text-white undefined undefined
      textStyles: text-white mg-copy-small undefined
      buttonType: primary
      buttonIcon: arrow-right-solid
      buttonLayout: undefined
      buttonWidth: undefined
    background:
      fillStyles: bg-black opacity-100
      wrapFillStyles: bg-gray-dark opacity-100
      style: bg-cover
      position: bg-center
      ornaments:
        - src: /uploads/rule.svg
          alignment: bottom
    label: ''
    headline: Features
    subhead: ''
    body: ''
    items:
      - image:
          src: /uploads/bolt.svg
        headline: Work Quickly
        subhead: ''
        body: >
          Create custom-designed websites quickly with simple, intuitively
          editable stock components. Navigation, analytics, and SEO are
          built-in, so you can get started right away.
        link: ''
        buttonLabel: ''
      - image:
          src: /uploads/brush.svg
        headline: Complete Design Control
        subhead: ''
        body: >
          The theme layer gives you complete control over color, typography and
          buttons. See your design system on a beautifully presented stylesheet
          and view global changes in real time as you edit your site.
      - image:
          src: /uploads/image-polaroid.svg
        headline: Backgrounds Matter
        subhead: ''
        body: >
          Background control takes a layered approach for flexible control. Add
          a color or gradient background, place an image over it and layer an
          unlimited number of other images with precision placement.
      - image:
          src: /uploads/chart-network.svg
        headline: Endlessly Extendable
        body: >
          Take your site beyond stock components by adding your own. Customize
          content fields to fit your needs, add interactivity, call APIs, and
          make it your own. Familiar tools like React and Tailwind lower the
          learning curve.
      - image:
          src: /uploads/mobile.svg
        headline: Mobile Friendly
        body: >
          Sites are mobile ready with full featured mobile navigation, and
          complete control over mobile typography, size and spacing on both the
          theme and component level. Tweak the mobile view of your site to your
          heart’s content.
      - image:
          src: /uploads/unlock.svg
        headline: No Lock-In
        body: >
          Microgen was built for Protocol Labs and designed for the
          decentralized internet. Customize it how you choose and host your site
          on any static host including IPFS. It's yours, for free and forever.
    navigationLabel: features
    _template: cards
  - style:
      alignment: >-
        flex-col-reverse items-center gap-6 sm:flex-col-reverse sm:items-center
        sm:gap-12
      padding: 'pt-20 pb-20 pr-14 pl-14 sm:pt-10 sm:pb-10 sm:pr-5 sm:pl-5'
      featureContent: 'w-2/3 min-h-0 text-center sm:w-full sm:min-h-0 sm:text-center'
      buttonsLayout: 'flex-row  '
      labelStyles: text-white undefined undefined
      headlineStyles: text-white mg-headline-large undefined
      subheadStyles: text-white undefined undefined
      textStyles: text-white mg-copy-small undefined
    cardStyle:
      fillStyles: ' opacity-100'
      grid: >-
        grid-cols-4 justify-start gap-12 sm:grid-cols-2 sm:justify-start
        sm:gap-4
      alignment: flex-col items-start  text-left
      image: wpx-48 hpx-48 object-center object-fill
      imagePadding: pt-0 pb-0 pr-0 pl-0
      contentPadding: pt-5 pb-0 pr-0 pl-0
      borderStyles: border-white border-0
      labelStyles: text-white undefined undefined
      headlineStyles: text-white mg-headline-medium undefined
      subheadStyles: text-white undefined undefined
      textStyles: text-white mg-copy-small undefined
      buttonLayout: undefined
      buttonWidth: undefined
    background:
      fillStyles: ' opacity-100'
      style: bg-cover
      position: bg-center
      ornaments:
        - src: /uploads/rule.svg
          alignment: bottom
    label: ''
    headline: 'Built on a foundation of fast, production-grade tooling'
    subhead: ''
    body: ''
    items:
      - image:
          src: /uploads/react.svg
        headline: React
        subhead: ''
        body: >
          A free and open-source front-end JavaScript library for building user
          interfaces based on components.
      - image:
          src: /uploads/next-js.svg
          alt: Next JS
        headline: Next JS
        subhead: ''
        body: >
          Create full-stack Web applications by extending the latest React
          features and JavaScript tooling.
      - image:
          src: /uploads/tailwind.svg
          alt: Tailwind
        headline: Tailwind
        subhead: ''
        body: >
          A utility-first CSS framework that can be used to build any design,
          directly in your markup.
      - image:
          src: /uploads/tina.svg
        headline: Tina CMS
        body: |
          Tina is an open-source, headless CMS for Markdown, MDX, and JSON.
    navigationLabel: tooling
    _template: cards
  - style:
      alignment: >-
        flex-col-reverse items-center gap-6 sm:flex-col-reverse sm:items-center
        sm:gap-12
      padding: 'pt-20 pb-20 pr-14 pl-14 sm:pt-10 sm:pb-10 sm:pr-5 sm:pl-5'
      featureContent: 'w-2/3 min-h-0 text-center sm:w-full sm:min-h-0 sm:text-center'
      buttonsLayout: 'flex-row  '
      labelStyles: text-white undefined undefined
      headlineStyles: text-white mg-headline-large undefined
      subheadStyles: text-white undefined undefined
      textStyles: text-white undefined undefined
    cardStyle:
      fillStyles: ' opacity-100'
      grid: >-
        grid-cols-4 justify-start gap-12 sm:grid-cols-2 sm:justify-start
        sm:gap-6
      alignment: flex-col items-start  text-left
      image: wpx-36 hpx-36 object-center object-fill
      imagePadding: pt-0 pb-0 pr-0 pl-0
      contentPadding: pt-5 pb-0 pr-0 pl-0
      borderStyles: border-white border-0
      labelStyles: text-white undefined undefined
      headlineStyles: text-white mg-headline-medium undefined
      subheadStyles: text-white undefined undefined
      textStyles: text-white mg-copy-small undefined
      buttonLayout: undefined
      buttonWidth: undefined
    background:
      fillStyles: ' opacity-100'
      wrapFillStyles: ' opacity-100'
      style: bg-cover
      position: bg-center
      ornaments:
        - src: /uploads/rule.svg
          alignment: bottom
    label: ''
    headline: Components (Sponsors Section?)
    subhead: ''
    body: ''
    items:
      - headline: Sponsor
        body: |
          ![](</uploads/IMG_0965 2.PNG>)
      - headline: Sponsor
        body: |
          ![](</uploads/IMG_0965 2.PNG>)
      - headline: Sponsor
        body: |
          ![](</uploads/IMG_0965 2.PNG>)
      - headline: Sponsor
        body: |
          ![](</uploads/IMG_0965 2.PNG>)
      - image:
          src: ''
        headline: Feature
        subhead: ''
        body: >
          THIS IS A TEST FOR SPONSOR SLOT


          Copy next to an image, or above an image. Or below it - you get the
          point. The core component of all websites.![](</uploads/IMG_0965
          2.PNG>)
        link: digi-frontier.com
      - image:
          src: /uploads/bring-forward.svg
        headline: Cards
        subhead: ''
        body: >
          A grid of cards. Each one with an image and text - a whole family of
          baby features. Incredibly customizable.
      - image:
          src: /uploads/distribute-spacing-vertical.svg
        headline: Accordion
        body: >
          A list of collapsible headline/text sets. Use them for FAQs,
          directions or list your bands favorite foods.
      - image:
          src: /uploads/video.svg
        headline: Embed
        body: >
          An open ended component for your own HTML with Tailwind styles. Forms,
          videos or anything else you can imagine.
      - image:
          src: /uploads/calendar.svg
        headline: Schedule
        body: >
          A full featured event calendar generated from event posts. Location
          details, time slots, categories and more.
      - image:
          src: /uploads/timeline.svg
        headline: Timeline
        subhead: ''
        body: >
          This is a simplified way of sharing event posts. An easy to read
          overview of the day or month's schedule.
    navigationLabel: components
    _template: cards
  - style:
      alignment: 'flex-col-reverse items-center '
      padding: pt-20 pb-20 pr-10 pl-10
      featureImage: '  mx-auto'
      featureContent: w-1/2 min-h-0 text-left
      buttonsLayout: 'flex-row  '
      labelStyles: text-white undefined undefined
      headlineStyles: text-white undefined undefined
      subheadStyles: text-white undefined undefined
      textStyles: text-white undefined undefined
    background:
      style: bg-cover
      position: bg-center
    image:
      src: /uploads/IMG_0968 2.PNG
    headline: Headline
    subhead: Subhead
    _template: feature
  - style:
      alignment: 'flex-row-reverse items-center gap-12 sm:flex-col sm:items-center sm:'
      padding: 'pt-32 pb-32 pr-14 pl-14 sm:pt-0 sm:pb-10 sm:pr-5 sm:pl-5'
      featureImage: '  mr-auto   sm:mx-auto'
      featureContent: 'w-3/5 min-h-0 text-left sm:w-full sm:min-h-0 sm:text-left'
      buttonsLayout: 'flex-row  '
      labelStyles: text-white undefined undefined
      headlineStyles: text-white mg-headline-large undefined
      subheadStyles: text-white undefined undefined
      textStyles: text-white mg-copy undefined
    background:
      fillStyles: ' opacity-100'
      wrapFillStyles: ' opacity-100'
      style: bg-cover
      position: bg-center
      ornaments:
        - src: /uploads/rule.svg
          alignment: bottom
    image:
      src: /uploads/collections.mp4
    headline: Collections
    subhead: ''
    body: >
      Go beyond pages and add data as events or posts. Events can be displayed
      in a feature rich schedule component, timeline or as cards. Create any
      other data collection you like to manage team members, products or
      anything else you can imagine. The data structure of these collections is
      completely up to you.
    navigationLabel: collections
    _template: feature
  - style:
      alignment: 'flex-row-reverse items-center  sm:flex-col sm:items-center sm:'
      padding: 'pt-32 pb-32 pr-14 pl-14 sm:pt-10 sm:pb-14 sm:pr-5 sm:pl-5'
      featureImage: '  mx-auto'
      featureContent: w-full min-h-0 text-left
      buttonsLayout: 'flex-row  '
      labelStyles: text-white undefined undefined
      headlineStyles: text-white mg-headline-large undefined
      subheadStyles: text-white undefined undefined
      textStyles: text-white mg-copy undefined
    background:
      fillStyles: ' opacity-100'
      style: bg-cover
      position: bg-center
      ornaments:
        - src: /uploads/rule.svg
          alignment: bottom
    headline: Get Started
    subhead: ''
    body: |
      1. Clone the project repo and upload it to your choice of static host
      2. Create a **[Free Tina CMS account](https://tina.io/ "Tina CMS")**
      3. Start stacking up components to create your pages
    buttons:
      - label: Documentation
        link: 'https://github.com/MicrogenSite/microgen'
        buttonStyle: primary
    navigationLabel: ''
    _template: feature
  - style:
      fullWidth: false
      minHeight: min-h-100
      padding: pt-20 pb-20 pr-10 pl-10
      labelStyles: text-white undefined undefined
      headlineStyles: text-white undefined undefined
      subheadStyles: text-white undefined mb-4
      textStyles: text-white undefined undefined
    background:
      fillStyles: from-black to-black bg-gradient-to-r opacity-100
      wrapFillStyles: from-white to-black bg-gradient-to-r opacity-100
      src: ''
      style: bg-cover
      position: bg-center
    _template: eventTimeline
  - style:
      fullWidth: false
      minHeight: undefined
      padding: pt-0 pb-0 undefined pl-96
    background:
      fillStyles: from-white to-primary bg-gradient-to-r opacity-100
      wrapFillStyles: ' opacity-100'
      src: /uploads/hero-video.jpg
      style: bg-cover
      position: bg-center
    markup: >
      <div id="mc_embed_shell">
            <link href="//cdn-images.mailchimp.com/embedcode/classic-061523.css" rel="stylesheet" type="text/css">
        <style type="text/css">
              #mc_embed_signup{background:#fff; false;clear:left; font:14px Helvetica,Arial,sans-serif; width: 600px;}
              /* Add your own Mailchimp form style overrides in your site stylesheet or in this style block.
                 We recommend moving this block and the preceding CSS link to the HEAD of your HTML file. */
      </style>

      <div id="mc_embed_signup">
          <form action="https://digi-frontier.us21.list-manage.com/subscribe/post?u=0d1bcaff99644bd5e76a8611f&amp;id=23f347c4e2&amp;f_id=008d5fe1f0" method="post" id="mc-embedded-subscribe-form" name="mc-embedded-subscribe-form" class="validate" target="_blank">
              <div id="mc_embed_signup_scroll"><h2>Subscribe</h2>
                  <div class="indicates-required"><span class="asterisk">*</span> indicates required</div>
                  <div class="mc-field-group"><label for="mce-FNAME">First Name </label><input type="text" name="FNAME" class=" text" id="mce-FNAME" value=""></div><div class="mc-field-group"><label for="mce-LNAME">Last Name </label><input type="text" name="LNAME" class=" text" id="mce-LNAME" value=""></div><div class="mc-field-group"><label for="mce-EMAIL">Email Address <span class="asterisk">*</span></label><input type="email" name="EMAIL" class="required email" id="mce-EMAIL" value="" required=""></div>
              <div id="mce-responses" class="clear foot">
                  <div class="response" id="mce-error-response" style="display: none;"></div>
                  <div class="response" id="mce-success-response" style="display: none;"></div>
              </div>
          <div aria-hidden="true" style="position: absolute; left: -5000px;">
              /* real people should not fill this in and expect good things - do not remove this or risk form bot signups */
              <input type="text" name="b_0d1bcaff99644bd5e76a8611f_23f347c4e2" tabindex="-1" value="">
          </div>
              <div class="optionalParent">
                  <div class="clear foot">
                      <input type="submit" name="subscribe" id="mc-embedded-subscribe" class="button" value="Subscribe">
                      <p class="brandingLogo" style="margin: 0px auto;"><a href="http://eepurl.com/ivTUd2" title="Mailchimp - email marketing made easy and fun"><img src="https://eep.io/mc-cdn-images/template_images/branding_logo_text_dark_dtp.svg" alt="referral badge"></a></p>
                  </div>
              </div>
          </div>
      </form>

      </div>

      <script type="text/javascript"
      src="//s3.amazonaws.com/downloads.mailchimp.com/js/mc-validate.js"></script><script
      type="text/javascript">(function($) {window.fnames = new Array();
      window.ftypes = new
      Array();fnames[1]=FNAME;ftypes[1]=merge;,fnames[2]=LNAME;ftypes[2]=merge;,fnames[0]=EMAIL;ftypes[0]=merge;,fnames[3]=ADDRESS;ftypes[3]=merge;,fnames[4]=PHONE;ftypes[4]=merge;,fnames[5]=BIRTHDAY;ftypes[5]=merge;false}(jQuery));var
      $mcj = jQuery.noConflict(true);</script></div>
    _template: embed
  - style:
      alignment: 'flex-col-reverse items-center '
      padding: 'pt-20 pb-20 pr-5 pl-5 sm:pt-10 sm:pb-10 sm:pr-5 sm:pl-5'
      featureImage: '  mx-auto'
      featureContent: 'w-3/4 min-h-0 text-center sm:w-full sm:min-h-0 sm:text-center'
      buttonsLayout: 'flex-row  '
      labelStyles: text-white undefined undefined
      headlineStyles: text-white mg-headline-large mb-10
      subheadStyles: text-white undefined undefined
      textStyles: text-white mg-copy undefined
    background:
      fillStyles: ' opacity-100'
      style: bg-cover
      position: bg-center
      ornaments:
        - src: /uploads/rule.svg
          alignment: bottom
    headline: Credits
    subhead: ''
    body: >
      ![](/uploads/bustout-protocol-partners.svg)


      Microgen was built by **[Bust Out](https://bustout.com "Bust Out")** for
      **[Protocol Labs](https://protocol.ai "Protocol Labs")** and designed to
      run on **[IPFS](https://ipfs.tech/ "IPFS")**. It’s based on the excellent
      and open source **[Tina CMS](https://tina.io "Tina CMS")**.
    _template: feature
backgroundColor: white
meta:
  title: Microgen
  description: ''
background:
  fillStyles: bg-black opacity-100
  src: ''
  style: bg-cover
  position: bg-left
---



















