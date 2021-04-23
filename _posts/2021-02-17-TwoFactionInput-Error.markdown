---
layout: post
title:  "Verification Code - Incorrect Code"
date:   2021-02-17 10:40:48 -0310
categories: jekyll update
---
<div class="bg_acc flex justify_center texture_dust m-b_5">
<div class="b_n3 bg_alert br_3 br_circle br_solid br_white-9 flex_none m-b_n5 m-t_5 m-x_auto p_3 shadow_overlap-light c_white " style="width:100px;height:100px;align-content: center; justify-content: center; display: grid;">
    <span class="c_white  font_5">
            <i class="fas fa-times"></i>
            </span>  
</div>
</div>
<div class="m_auto max-w_30 p-y_5">
<div class="reading-typography">
<h1>That Code Seems to be Incorrect</h1>
<p class="font_1">Make sure it was typed correctly.</p>
<ul class="ul_none"><li><a class="link c_primary-n1">Send a new code.</a></li><li><a class="link c_primary-n1"><a class="link c_primary-n1">Change authentication modes.</a>.</a></li>
</ul>
</div>
<fieldset class="question font_ui br_none">
    <legend
            class="label-holder flex font-size_up font_medium p-y_2">
        <!----> <span class="flex_shrink">Verification Code
        </span>
    </legend>
    <div class="flex flex_row justify_center">
    {% include digitInputError.html %}
    </div>
     <div  class="message-holder font-size_down  c_alert-n1 clear_both">
     <div class="p_2 font_bold inline-flex "><div class="flex justify_center flex_none font-size_down m-r_3 texture_dust c_white bg_alert-n2 " style="width: 2em; height: 2em;"><i class="fas text_center flex_auto self_center lh_0 fa-times"></i></div> <div class="flex flex_column justify_center"><div>That code was incorrect. </div></div></div></div>
    </fieldset>
{% include confirmButton.html %}

</div>
<div class="br-t_1 br_solid br_black-3 bg_black-1 text_center p_3 m-t_auto shadow_n2"><a class="link c_primary-n1">Contact NCDR Support</a></div>