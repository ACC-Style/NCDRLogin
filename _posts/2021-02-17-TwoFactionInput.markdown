---
layout: post
title:  "Two Factor Input"
date:   2021-02-17 10:40:48 -0500
categories: jekyll update
---
<div class="bg_acc flex justify_center texture_dust m-b_5">
<div class="b_n3 bg_primary br_3 br_circle br_solid br_white-9 flex_none m-b_n5 m-t_5 m-x_auto p_3 shadow_overlap-light c_white " style="width:100px;height:100px;align-content: center;justify-content: center;display: grid;">
<i class="fas fa-mobile-alt font_8 c_white"></i>
</div>
</div>
<div class="m_auto max-w_30 p-y_5">
<div class="reading-typography">
<h1>Code Sent</h1>
<p class="font_1">We have sent you a 6-digit verification code.</p>
</div>
<fieldset class="question font_ui br_none">
    <legend
            class="label-holder flex font-size_up font_medium p-y_2">
        <!----> <span class="flex_shrink">Verification Code
        </span>

    </legend>
    <div class="flex flex_row justify_center">
    {% include digitInput.html %}
    </div>
    </fieldset>
{% include confirmButton.html %}

</div>
<div class="br-t_1 br_solid br_black-3 bg_black-1 text_center p_3 m-t_auto shadow_n2"><a class="link c_primary-n1">I didn't receive a code.</a> |
<a class="link c_primary-n1">Change my secondary authentication mode.</a></div>