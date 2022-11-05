---
layout: page
title: Planetarium Shows Booking
subtitle: Explore the cosmos with us!
cover-img: /assets/img/banner/planetarium.gif
---

Enjoy the beauty of our planet, the solar system, the galaxy and the universe under the award winning largest completely student built planetarium in the whole of Asia. Brownie points to us for being the only SnT Council entity having an Air Conditioner in the room, so you can be sure that your experience will be terrific!

## Where is the planetarium?

The clubroom itself is a planetarium! Want to see it yourself? Come up to Room 401, New SAC, IIT Kanpur to witness the magic.

<div class="mapouter" style="margin-bottom:30px"><div class="gmap_canvas"><iframe class="gmap_iframe" width="100%" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" src="https://maps.google.com/maps?width=1080&amp;height=720&amp;hl=en&amp;q=Astronomy Club, IIT Kanpur&amp;t=&amp;z=14&amp;ie=UTF8&amp;iwloc=B&amp;output=embed"></iframe></div><style>.mapouter{position:relative;text-align:right;width:100%;height:400px;}.gmap_canvas {overflow:hidden;background:none!important;width:100%;height:400px;}.gmap_iframe {height:400px!important;}</style></div>

## Book your seats!

Don't worry! It's completely free of cost. Timings will be allotted on a first come, first serve basis. Kindly wait a few seconds after clicking 'Submit'.

<form style="margin-bottom:40px" method="POST" name="google-sheet">
    <input name="Full Name" required="true" type="text" placeholder="Full name" />
    <input name="Roll Number" required="true" type="number" placeholder="Roll number" />
    <input name="IITK CC Username" required="true" type="text" placeholder="IITK CC Username" />

    <div style="display:flex; flex-direction:row; justify-content:space-between">
        <button type="submit">Submit</button>
        <button type="reset">Reset</button>
    </div>
</form>

## Confirmation

Your booking and timings, once confirmed by our team, will be sent to you via E-Mail.

<script>
    const scriptURL = '';
    const form = document.forms['google-sheet'];

    form.addEventListener('submit', e => {
        e.preventDefault();
        fetch(scriptURL, { method: 'POST', body: new FormData(form) })
            .then(res => {
                alert('Form submitted successfully!');
                form.reset();
                console.log(res)
            })
            .catch(err => {
                alert('Snap! Something went wrong..')
                console.log(err.message)
            })
    });
</script>