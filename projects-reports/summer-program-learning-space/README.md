# Summer Program Learning Space Development

## Project Overview

This project involved the development of a Canvas learning space for the JSI Summer 2024 program. The space branches out to 5 courses and includes a customized home page to facilitate easy navigation and access to program resources.


## Project Features
Custom Home Page: A visually appealing and functional home page that provides easy access to the program calendar, team information, Canvas support, and resources.
Courses: Links to the five courses offered in the summer program: Policy Analysis, Quantitative Methods, Economics for Policy Analysis, Leadership & Community Engagement, and Mini Capstone Project.
Welcome Section: An informative welcome message explaining the purpose of the Canvas LMS for the JSI program.
Our 2024 Scholars: Information about the JSI program's goals and the benefits for participants, along with an embedded Google presentation.
## Project Details

### Home Page Code

```html
<div id="dp-wrapper" class="dp-wrapper">
    <div id="kl_wrapper_3" class="kl_apple kl_wrapper">
        <h2 id="kl_introduction"></h2>
        <div id="kl_banner_image" class="">
            <header>
                <div style="background-color: #32006e; padding: 40px; border-radius: 5px; position: relative; text-align: left;">
                    <div style="background-color: white; padding: 10px 20px; display: inline-block;">
                        <h2 style="margin: 0;"><span style="font-size: 18pt;">JSI Summer 2024!</span></h2>
                    </div>
                </div>
            </header>
            <hr />
            <div id="kl_activities2" class="">
                <p style="text-align: center;"><a class="inline_disabled btn-lg bs-btn bs-btn-dark bs-btn-lg" style="margin-right: 4px; background-color: black; color: white;" href="https://canvas.uw.edu/courses/1768989/pages/program-calendar" target="_blank" rel="noopener" data-api-endpoint="https://canvas.uw.edu/api/v1/courses/1768989/pages/program-calendar" data-api-returntype="Page"> Program Calendar&nbsp; &nbsp; </a> <a class="inline_disabled btn-lg bs-btn bs-btn-dark bs-btn-lg" style="margin-right: 4px; background-color: black; color: white;" title="Program Team" href="https://canvas.uw.edu/courses/1768989/pages/program-team" target="_blank" rel="noopener" data-api-endpoint="https://canvas.uw.edu/api/v1/courses/1768989/pages/program-team" data-api-returntype="Page"> Program Team&nbsp; &nbsp; &nbsp; </a> <a class="inline_disabled bs-btn bs-btn-dark bs-btn-lg" style="margin-right: 4px; background-color: black; color: white;" href="https://canvas.uw.edu/courses/1768989/pages/technology-support-and-resources" target="_blank" rel="noopener" data-api-endpoint="https://canvas.uw.edu/api/v1/courses/1768989/pages/technology-support-and-resources" data-api-returntype="Page"> Canvas Support&nbsp; &nbsp; </a> <a class="inline_disabled bs-btn bs-btn-dark bs-btn-lg" style="background-color: black; color: white;" href="https://canvas.uw.edu/courses/1768989/pages/resources" target="_blank" rel="noopener" data-api-endpoint="https://canvas.uw.edu/api/v1/courses/1768989/pages/resources" data-api-returntype="Page"> Resources&nbsp; &nbsp; &nbsp; </a></p>
            </div>
            <hr />
            <div id="kl_readings2" class="" style="background-color: #f4f4f4; padding: 20px; border-radius: 5px;">
                <h3 class="" style="background-color: #4b2e83; color: #ffffff;">Welcome!</h3>
                <p>This is Canvas, our Learning <strong>Management System (LMS)</strong> for all <strong>Junior Summer Institute (JSI)</strong> programs and learning-related activities. If you are not familiar with Canvas, we invite you to read the <a class="inline_disabled" href="https://community.canvaslms.com/t5/Student-Guide/tkb-p/student" target="_blank" rel="noopener">how-to instruction</a> which provides step-by-step instructions for navigating Canvas. This is a one-stop shop for JSI program resources, including courses, assignments, weekly program schedules, and resources, including those shared by presenters.</p>
                <p>Our JSI instructional home is Parrington Hall and all meetings will take place there unless indicated on the schedule.</p>
            </div>
            <div id="kl_lectures2" class="">
                <p style="background-color: #ffffff; color: #000000; border-style: none;">&nbsp;</p>
                <h3 class="" style="background-color: #ffffff; color: #000000; border-style: none;">Courses</h3>
                <table style="border-collapse: collapse; width: 100%; height: 23px; margin-left: auto; margin-right: auto;">
                    <tbody>
                        <tr>
                            <td class="" style="width: 20%; text-align: center; border-style: none; padding: 0 10px;"><a class="" title="Policy Analysis, Implementation, &amp; Program Evaluation" href="https://canvas.uw.edu/courses/1768989/pages/policy-analysis-implementation-and-program-evaluation-2" data-course-type="wikiPages" data-published="true" data-api-endpoint="https://canvas.uw.edu/api/v1/courses/1768989/pages/policy-analysis-implementation-and-program-evaluation-2" data-api-returntype="Page"> <img class="kl_rounded_5 dp-image-round" style="width: 133px; height: auto;" role="presentation" src="https://canvas.uw.edu/courses/1768989/files/120233833/download" alt="" width="133" height="145.438" data-api-endpoint="https://canvas.uw.edu/api/v1/courses/1768989/files/120233833" data-api-returntype="File" /> </a></td>
                            <td class="" style="width: 20%; text-align: center; border-style: none; padding: 0 10px;"><a title="Quantitative Methods for Policy Making" href="https://canvas.uw.edu/courses/1768989/pages/quantitative-methods-for-policy-making" data-api-endpoint="https://canvas.uw.edu/api/v1/courses/1768989/pages/quantitative-methods-for-policy-making" data-api-returntype="Page"> <img class="kl_rounded_5 dp-image-round" style="width: 133px; height: auto;" role="presentation" src="https://canvas.uw.edu/courses/1768989/files/120233830/download" alt="" width="133" height="144.625" data-api-endpoint="https://canvas.uw.edu/api/v1/courses/1768989/files/120233830" data-api-returntype="File" /> </a></td>
                            <td class="" style="width: 20%; text-align: center; border-style: none; padding: 0 10px;"><a title="Economics for Policy Analysis" href="https://canvas.uw.edu/courses/1768989/pages/economics-for-policy-analysis" data-api-endpoint="https://canvas.uw.edu/api/v1/courses/1768989/pages/economics-for-policy-analysis" data-api-returntype="Page"> <img class="kl_rounded_5 dp-image-round" style="width: 133px; height: auto;" role="presentation" src="https://canvas.uw.edu/courses/1768989/files/120233834/download" alt="" width="133" height="144.344" data-api-endpoint="https://canvas.uw.edu/api/v1/courses/1768989/files/120233834" data-api-returntype="File" /> </a></td>
                            <td style="width: 20%; text-align: center; border-style: none; padding: 0 10px;"><a title="Leadership &amp; Community Engagement" href="https://canvas.uw.edu/courses/1768989/pages/leadership-and-community-engagement" data-api-endpoint="https://canvas.uw.edu/api/v1/courses/1768989/pages/leadership-and-community-engagement" data-api-returntype="Page"> <img class="kl_rounded_5 dp-image-round" style="width: 133px; height: auto;" role="presentation" src="https://canvas.uw.edu/courses/1768989/files/120233831/download" alt="" width="133" height="146.531" data-api-endpoint="https://canvas.uw.edu/api/v1/courses/1768989/files/120233831" data-api-returntype="File" /> </a></td>
                            <td class="" style="width: 20%; text-align: center; border-style: none; padding: 0 10px;"><a title="Mini Capstone Project" href="https://canvas.uw.edu/courses/1768989/pages/mini-capstone-project" data-course-type="wikiPages" data-published="false" data-api-endpoint="https://canvas.uw.edu/api/v1/courses/1768989/pages/mini-capstone-project" data-api-returntype="Page"> <img class="dp-image-round" style="width: 152px; height: 139px;" role="presentation" src="https://canvas.uw.edu/courses/1768989/files/121387243/download" alt="" width="150" height="136.703" data-api-endpoint="https://canvas.uw.edu/api/v1/courses/1768989/files/121387243" data-api-returntype="File" /> </a></td>
                        </tr>
                    </tbody>
                </table>
            </div>
            &nbsp;
            <div id="kl_objectives2" class="" style="background-color: #f4f4f4; padding: 20px; border-radius: 5px;">
                <h3 class="" style="background-color: #4b2e83; color: #ffffff;">Our 2024 Scholars</h3>
                <p><span>The Evans School JSI program is designed to broaden participants' academic and professional horizons. In addition to interacting with and learning from talented peers, JSI participants learn to analyze and evaluate international and domestic policies under the guidance of experienced policy practitioners and academics. Combining analytic skills and substantive knowledge about contemporary policy issues will provide undergraduates with excellent preparation for graduate programs in public policy. <em><strong>We are happy you are here!&nbsp;</strong></em></span></p>
                <p style="text-align: center;">&nbsp;</p>
                <div class="kl_iframe_wrapper kl_iframe_align_center kl_iframe_responsive_scale">
                    <div class="dp-embed-wrapper"><iframe src="https://docs.google.com/presentation/d/e/2PACX-1vQmlob5EnsV71IvHrCb-0IuLhLpmTQJYcqKvobtwa6yWtgZ56VFIrM10bmEFCZsAV33nT0Tfik80AQA/embed?start=false&amp;loop=false&amp;delayms=3000" width="1280" height="749" allowfullscreen="allowfullscreen" webkitallowfullscreen="webkitallowfullscreen" mozallowfullscreen="mozallowfullscreen"></iframe></div>
                </div>
            </div>
        </div>
    </div>
    <p><img class="" role="presentation" src="https://canvas.uw.edu/courses/1768989/files/120233716/download" alt="" data-api-endpoint="https://canvas.uw.edu/api/v1/courses/1768989/files/120233716" data-api-returntype="File" /></p>
    <footer style="text-align: center; margin-top: 20px; font-size: small;">&copy; Evans School 2024</footer>
</div>
