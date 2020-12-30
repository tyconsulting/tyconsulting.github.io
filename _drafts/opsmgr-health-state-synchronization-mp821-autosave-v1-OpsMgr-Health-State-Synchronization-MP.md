---
id: 836
title: OpsMgr Health State Synchronization MP
date: 2015-04-19T17:14:26+10:00
author: Tao Yang
layout: revision
guid: http://www.tyconsulting.com.au/821-autosave-v1/
permalink: /821-autosave-v1/
---
<img loading='lazy' class='alignleft wp-image-843 size-full' src='http://www.tyconsulting.com.au/wp-content/uploads/2015/04/HealthSync80.png' alt='HealthSync80' width='80' height='80' />It is common to have multiple OpsMgr management groups in large organizations. When designing distributed application or creating custom dashboards, one of the limitations is that OpsMgr users can only select monitoring objects within the local management group to be a part of the Health Model. This becomes an issue when users want to design a Distributed Application or dashboard that include components monitored by different OpsMgr management groups.

The **OpsMgr Health Synchronization Library** management pack is designed to provide a workaround to this limitation. This management pack provides a template that enables OpsMgr users to create monitoring objects named '**Health State Watcher**' hosted by All Management Servers Resource Pool. Health State Watcher objects have monitors configured to query health state of monitoring objects located in a remote management group using OpsMgr SDK.

[<img loading='lazy' class=' size-large wp-image-838 aligncenter' src='http://www.tyconsulting.com.au/wp-content/uploads/2015/04/HealthStateSyncMPDiagram-700x311.png' alt='HealthStateSyncMPDiagram' width='700' height='311' srcset='http://www.tyconsulting.com.au/wp-content/uploads/2015/04/HealthStateSyncMPDiagram-700x311.png 700w, http://www.tyconsulting.com.au/wp-content/uploads/2015/04/HealthStateSyncMPDiagram-450x200.png 450w, http://www.tyconsulting.com.au/wp-content/uploads/2015/04/HealthStateSyncMPDiagram-250x111.png 250w, http://www.tyconsulting.com.au/wp-content/uploads/2015/04/HealthStateSyncMPDiagram-512x227.png 512w, http://www.tyconsulting.com.au/wp-content/uploads/2015/04/HealthStateSyncMPDiagram.png 997w' sizes='(max-width: 700px) 100vw, 700px' />](http://www.tyconsulting.com.au/wp-content/uploads/2015/04/HealthStateSyncMPDiagram.png)

As shown in the diagram above, an instance of Health State Watcher can be created for each monitoring object of user's choice from a remote management group. Each Health State Watcher object will periodically update its own health state based on the health state of the remote monitoring object it is watching for (every 5 minutes by default). As shown above, the Health State Watcher can query health state of any monitoring objects from remote management group (i.e. a Windows Computer object, a Distributed Application or any other types monitoring objects).

This management pack provides 4 unit monitors to the Health State Watcher class. They are used to query the health state of the **Availability**, **Configuration**, **Performance** and **Security** aggregate monitors of the remote monitoring object respectively.

Once the Health State Watcher objects are created and correctly configured, it can be used to display the health state of the remote monitoring object in a dashboard or distributed application hosted by the local management group.

**Download OpsMgr Health State Synchronization Management Pack by filling out the form below. The download link will be emailed to you.**

**Please use your business email, free email providers such as Gmail, Hotmail etc. will not be accepted.**

<div role="form" class="wpcf7" id="wpcf7-f839-o8" lang="en-US" dir="ltr">
  <div class="screen-reader-response">
    <p role="status" aria-live="polite" aria-atomic="true">
    </p>
    
    <ul>
    </ul>
  </div>
</div> .</p>