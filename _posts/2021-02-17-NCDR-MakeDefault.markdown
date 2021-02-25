---
layout: post
title: "NCDR Set Default PID"
date: 2021-02-17 10:40:48 -0510
categories: jekyll update
---

<div class="bg_acc flex justify_center texture_dust m-b_5">
<div class="b_n3 bg_success br_3 br_circle br_solid br_white-9 flex_none m-b_n5 m-t_5 m-x_auto p_3 shadow_overlap-light c_white " style="width:100px;height:100px;align-content: center; justify-content: center;display: grid;">
            <span class="fa-stack c_white  font_5">
            <i class="fas fa-file fa-stack-2x"></i>
            <i class="fas fa-cog fa-stack-1x c_success m-t_3"></i>
            </span>  
</div>
</div>
<div class="m_auto max-w_30 p-y_5">
<h1>Registries</h1>
<p>You have access to more than one registry. </p>
    <fieldset>
    <legend
            class="label-holder flex font-size_up font_medium p-y_2">
        <!----> <span class="flex_shrink">Please enter your participant ID
        </span>
    </legend>
    <div class="flex flex_row justify_center">
    {% include digitInput.html %}
    </div>
    </fieldset>
{% include confirmButton.html %}
</div>
<div class="br-t_1 br_solid br_black-3 bg_black-1 text_center p_3 m-t_auto shadow_n1"><a class="link c_primary-n1">I don't see my registry</a></div>
<div class="absolute b_0 bg_black-7 l_0 r_0 t_0 z_5">
<div class="bg_white flex flex_column justify_start m-t_5 m-x_auto m-y_5 m-y_auto max-w_35 shadow_overlap-bold">
<div class="flex_shirink p_5">
<h1>Do you want to make this your default participant ID?</h1>
<p class="font_1">This will auto direct you to that participant space directly after login going forward.</p>
<div class="text_center m-b_4">
    <button class="ease_out transition_1 f:outline_none text_center br_none inline-block w_auto font_medium p-y_3 lh_2 p-x_4 font_1 font_2:md  c_white h:c_white h:bg_primary-n2 br_primary-n3 bg_primary shadow_overlap-light br_radius m_3" label="Log In"><span class="flex block justify_center">
        <span>YES</span></span></button>
    <button class="ease_out transition_1 f:outline_none text_center br_none inline-block w_auto font_medium p-y_3 lh_2 p-x_4 font_1 font_2:md  c_white h:c_white h:bg_shade-n2 br_shade-n3 bg_shade shadow_overlap-light br_radius m_3" label="Log In"><span class="flex block justify_center">
            <span>No</span></span></button>
</div>
</div>
<div class="bg_black-1 br-t_1 br_black-3 br_solid flex_none p_3 shadow_n2 text_center"><a class="link c_primary-n1">Don't show this to me again.</a></div>
</div>
</div>
