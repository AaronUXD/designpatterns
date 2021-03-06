---
title: "File upload"
preview: true
---
<div class="pl-pattern">
### Single file upload
Single file upload, where the file is uploaded when the form is submitted. 


{::nomarkdown}
<div class="pl-preview">
<form action="" class="form-horizontal" style="max-width: 400px;">
    <div class="form-group">
        <label class="col-sm-3 control-label">File</label>
        <div class="col-sm-9">
            <div class="input-group">
                <div class="form-control"></div>
                <div class="input-group-btn">
                    <button type="button" class="btn btn-default">Select file...</button>
                </div>
            </div>
        </div>
    </div>
    <div class="form-group">
        <label class="col-sm-3 control-label">File</label>
        <div class="col-sm-9">
            <div class="input-group">
                <div class="form-control">IMG-209.jpg <span class="text-muted">(322 KB)</span></div>
                <div class="input-group-btn">
                    <button style="margin-left: -37px;" class="btn btn-default btn-hover"><i class="icon text-muted icon-close"></i></button>
                    <button type="button" class="btn btn-default">Select file...</button>
                </div>
            </div>
        </div>
    </div>
</form>
</div>
{:/nomarkdown}
</div>

<div class="pl-pattern">
### Multi file upload
This shows how to facilitate uploading multiple files to the same field (e.g., an attachments field), where the files are uploaded as soon as they're selected rather than when the form is submitted. 


{::nomarkdown}
<div class="pl-preview">
<form action="" class="form-horizontal" style="max-width: 400px;">
    <div class="form-group">
        <label class="col-sm-3 control-label">Attachments</label>
        <div class="col-sm-9">
            <button type="button" class="btn btn-default">Select file(s)...</button>
        </div>
    </div>
</form>
</div>
{:/nomarkdown}


{::nomarkdown}
<div class="pl-preview">
<form action="" class="form-horizontal" style="max-width: 400px;">
    <div class="form-group">
        <label class="col-sm-3 control-label">Attachments</label>
        <div class="col-sm-9">
            <div style="">
                <ul class="list-group" style="margin-bottom: 9px;">
                    <li class="list-group-item">
                        <a href=""><i style="" class="pull-right icon text-muted icon-close"></i></a>
                        IMG_209.jpg  <span class="text-muted">(322 KB)</span>
                    </li>
                    <li class="list-group-item">
                        <a href=""><i style="" class="pull-right icon text-muted icon-close"></i></a>
                        IMG_210.jpg  <span class="text-muted">(1.1 MB)</span>
                    </li>
                    <li class="list-group-item">
                        <a href=""><i style="" class="pull-right icon text-muted icon-close"></i></a>
                        IMG_211.jpg  <span class="text-muted">(5 MB)</span>
                        <div class="text-danger" style="margin: 2px 0 0 0">
                            This file exceeds the 2 MB limit.
                        </div>
                    </li>
                    <li class="list-group-item">
                        <a href=""><i style="" class="pull-right icon text-muted icon-close"></i></a>
                        IMG_212.jpg  <span class="text-muted">(312 KB)</span>
                        <div class="text-danger" style="margin: 2px 0 0 0">
                            Error uploading file.
                        </div>
                    </li>
                    <li class="list-group-item">
                        <a href=""><i style="margin-left: 4px;" class="pull-right icon text-muted icon-close"></i></a>
                        <span id="exampleProgressBarValue" class="pull-right text-muted">60%</span>
                        <div>IMG_213.jpg <span class="text-muted">(43 KB)</span></div>
                        <div class="progress" style="margin-bottom: 0; margin-top: 8px; clear: both;">
                          <div id="exampleProgressBar" class="progress-bar" role="progressbar" aria-valuenow="60" aria-valuemin="0" aria-valuemax="100" style="width: 60%;">
                          </div>
                        </div>
                    </li>
                </ul>
            </div> 
            <button type="button" class="btn btn-default">Select file(s)...</button>
        </div>
    </div>
</form>
</div>
{:/nomarkdown}


{::nomarkdown}
<div class="pl-preview">
<form action="" class="form-horizontal" style="max-width: 400px;">
    <div class="form-group">
        <label class="col-sm-3 control-label">Attachments</label>
        <div class="col-sm-9">
            <div style="">
                <ul class="list-group" style="margin-bottom: 9px;">
                    <li class="list-group-item">
                        <img style="margin-right: 8px; border: 3px solid #fff; margin-left: -4px; box-shadow: 0px 0px 0px 1px rgba(0,0,0,.1);" src="http://lorempixel.com/50/50/technics/3">
                        <a href=""><i style="" class="pull-right icon text-muted icon-close"></i></a>
                        IMG_209.jpg  <span class="text-muted">(322 KB)</span>
                    </li>
                    <li class="list-group-item">
                        <img style="margin-right: 8px; border: 3px solid #fff; margin-left: -4px; box-shadow: 0px 0px 0px 1px rgba(0,0,0,.1);" src="http://lorempixel.com/50/50/technics/4">
                        <a href=""><i style="" class="pull-right icon text-muted icon-close"></i></a>
                        IMG_210.jpg  <span class="text-muted">(1.1 MB)</span>
                    </li>
                    <li class="list-group-item">
                        <a href=""><i style="" class="pull-right icon text-muted icon-close"></i></a>
                        IMG_212.jpg  <span class="text-muted">(312 KB)</span>
                        <div class="text-danger" style="margin: 2px 0 0 0">
                            Error uploading file.
                        </div>
                    </li>
                </ul>
            </div> 
            <button type="button" class="btn btn-default">Select file(s)...</button>
        </div>
    </div>
</form>
</div>
{:/nomarkdown}
</div>
