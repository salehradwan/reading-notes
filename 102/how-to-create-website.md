1. # process and design
    1. It's important to understand who your target audience is, why they would come to your site, what information they want to find and when they are likely to return.
    1. Site maps allow you to plan the structure of a site.
    1. Wireframes allow you to organize the information that will need to go on each page.
    1. Design is about communication. Visual hierarchy helps visitors understand what you are trying to tell them.
    1. You can differentiate between pieces of information using size, color, and style.
    1. You can use grouping and similarity to help simplify the information you present.

## After answering these questions, you can imagine what the site looks like and draw it.

# After drawing it is delivered to the frontend programmer to design the website using HTML and CSS.

2. # HTML5 layout
    1. The new HTML5 elements indicate the purpose of different parts of a web page and help to describe its structure.
    1. The new elements provide clearer code (compared with using multiple <div> elements).
    1. Older browsers that do not understand HTML5 elements need to be told which elements are block-level elements.
    1. To make HTML5 elements work in Internet Explorer (and older versions of IE), extra JavaScript is needed,which is available free from Google.
3. # Extra markup
    1. DOCTYPES tell browsers which version of HTML youare using.
    1. You can add comments to your code between the `<!-- and -->` markers.
    1. Escape characters are used to include specialcharacters in your pages such as <, >, and ©.
```html
<!DOCTYPE html>
<html>
    <head>
        <title>
            Wirefram
        </title>
        <style>
            table {
                border-collapse: collapse;
            }
            td {
                border: 1px solid #000;
            }
        </style>
    </head>
    <body>
        <header style="text-align: center;">
            <img style="width: 150px;" src="https://p7.hiclipart.com/preview/656/554/407/social-media-logo-social-network-clip-art-classified-social-media.jpg" alt="">

            <nav>
                <a href="">1</a>
                <a href="">2</a>
                <a href="">3</a>
                <a href="">4</a>
                <a href="">5</a>
                <a href="">6</a>
            </nav>
        </header>
        <main>
            <section>
                
                <img style="width: 50%;" src="https://i1.wp.com/marketbusinessnews.com/wp-content/uploads/2019/07/Social-media-marketing-tool-small-businesses-image-4444.jpg?resize=965%2C691&ssl=1" alt="" align="right">
                <p> Social media are interactive digitally mediated technologies that facilitate the creation or sharing/exchange of information, ideas,career interests, and other forms of expression via virtual communities and networks.[1][2] While challenges to the definition of social media arise due to the broad variety of stand-alone and built-in social-media services currently available, there are some common features:[2]

                    Social media are interactive Web 2.0 Internet-based applications.[2][3]
                    User-generated content—such as text posts or comments, digital photos or videos, and data generated through all online interactions—is the lifeblood of social media.[2][3]
                    Users create service-specific profiles for the website or app that are designed and maintained by the social-media organization.[2][4]
                    Social media facilitate the development of online social networks by connecting a user's profile with those of other individuals or groups.[2][4]
                    Users usually access social media services via web-based apps on desktops and laptops, or download services that offer social media functionality to their mobile devices (e.g., smartphones and tablets). As users engage with these electronic services, they create highly interactive platforms through which individuals, communities, and organizations can share, co-create, discuss, participate, and modify user-generated content or self-curated content posted online.[1] Additionally, social media are used to document memories; learn about and explore things; advertise oneself; and form friendships along with the growth of ideas from the creation of blogs, podcasts, videos, and gaming sites.[5] This changing relationship between human and technology is the focus of the emerging field of technoself studies.
                    
                    Some of the most popular social media websites, with over 100 million registered users, include Facebook (and its associated Facebook Messenger), TikTok, WeChat, Instagram, QZone, Weibo, Twitter, Tumblr, Baidu Tieba, and LinkedIn. Depending on interpretation, other popular platforms that are sometimes referred to as social media services include YouTube, QQ, Quora, Telegram, WhatsApp, LINE, Snapchat, Pinterest, Viber, Reddit, Discord, VK, Microsoft Teams, and more. Wikis are examples of collaborative content creation.
                    
                    Social media outlets differ from traditional media (e.g., print magazines and newspapers, and TV and radio broadcasting) in many ways, including quality,[6] reach, frequency, usability, immediacy, and permanence.[7] Additionally, social media outlets operate in a dialogic transmission system (i.e., many sources to many receivers), while traditional media outlets operate under a monologic transmission model (i.e., one source to many receivers). For example, a newspaper is delivered to many subscribers and a radio station broadcasts the same programs to an entire city.[8]
                    
                    Since the dramatic expansion of the Internet, digital media or digital rhetoric can be used to represent or identify a culture. Studying how the rhetoric that exists in the digital environment has become a crucial new process for many scholars.
                    
                    Observers have noted a wide range of positive and negative impacts of social media use. Social media can help to improve an individual's sense of connectedness with real or online communities and can be an effective communication (or marketing) tool for corporations, entrepreneurs, non-profit organizations, advocacy groups, political parties, and governments. Observers have also seen that there has been a rise in social movements using social media as a tool for communicating and organizing in times of political unrest. 
                </p>
            </section>
            <section>
                <table>
                    <tr>
                        <td>Facebook</td>
                        <td>YouTube</td>
                        <td>WhatsApp</td>
                    </tr>
                    <tr>
                        <td>2,701</td>
                        <td>2,000</td>
                        <td>2,012</td>
                    </tr>
                </table>
                <article>
                    <ul>
                        <li>TikTok</li>
                        <li>QQ</li>
                        <li>WeChat</li>
                    </ul>
                </article>
                
            </section>
            <section>
                <form>
                    <label for="">username</label>
                    <input type="text">

                    <label for="">Password</label>
                    <input type="password">

                    <button>submit</button>
                </form>

                <ol>
                    <li>Google Classroom</li>
                    <li>Snapchat</li>
                    <li>Discord</li>
                    <li>Twitch</li>
                </ol>
            </section>
        </main>
        <footer>
            <p>all right reserved &copy;</p>
            <a href="https://www.facebook.com/">facebook</a>
            <a href="https://twitter.com/">twiter</a>
            <a href="https://www.instagram.com/">instagram</a>
        </footer>
    </body>
</html>
```