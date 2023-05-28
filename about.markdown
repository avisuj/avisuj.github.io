---
layout: page
title: About
permalink: /about/
---
> Avi Sujeeth, faithful man <br>
> Born in India, raised in US <br>
> Married to Missy, two kids <br>
> Abby, Isaac, his pride and joy <br>
> Passionate about Faith and Tech <br>
> Parenting, Investing, Legacy <br>
> Heart and integrity, his core values <br>
> Works at Microsoft, customer success <br>
> Focusing on patient experience <br>
> A life full of meaning and purpose. <br>
-[ChatGPT](https://chat.openai.com/chat)

## [Heart](https://avisuj.github.io/categories/heart)
One of my [core values](https://www.linkedin.com/pulse/my-core-values-integrity-heart-avi-sujeeth/), I live heart through connection and presence.  Throughout my life, I've struggled with depression.  I have come to embrace my melancholy - connecting through others in sadness and trial.  Attention.  I think one of the best gifts we can give each other is attention.  I want people to feel I cared.

## [Integrity](https://avisuj.github.io/categories/integrity)
Another [core value](https://www.linkedin.com/pulse/my-core-values-integrity-heart-avi-sujeeth/).  I live integrity through candor.  I try to be honest with myself.  I seek feedback.  I reflect.  I learn.

## [Faith](https://avisuj.github.io/categories/faith)
My family and my religion are a central part of my life.  Being an immigrant in the United States, there were many times I felt lonely; like I couldn't fit in where I lived or where I was born.  Through that period, the Catholic church gave me a sense of belonging and acceptance.  Participating in a community whose core tenants are to Love God and Love Your Neighbor has helped me pursue a "good life".  The gift of faith is something I hope to instill into my children.

## [Tech](https://avisuj.github.io/categories/tech)
I used my first computer when I was eight.  I participated in discussion boards on prodigy.  I watched streaming videos through a custom setup with Napster.  Alexa controls automates my home through a 40+ connected devices.  I wear two health trackers.  I let a robot make financial investments on my behalf.  I've subscribed to a precision health service.  I believe.  The majority of my career has been with Microsoft.  I've had the opportunity to see how technology can create change moments for organizations.  I've worked on problems including employee experience and patient experience. 

## [Parenting](https://avisuj.github.io/categories/parenting)
Leading my family has been one of my most rewarding jobs.  I enjoy watching my children become.  I try to leverage some of what I learn in my career to focus on the end game.  I can't wait to see how they change the world. 

## [Investing](https://avisuj.github.io/categories/investing)
When Microsoft recruited me in 2007, my salary increased by 500%.  That opportunity changed the direction of my life.  While living a modest lifestyle, we've been able to save significantly.  Now, we have four significant nest eggs: retirement accounts, real estate investments, equity investments, and crypto investments.  I'm hopeful that through compounding I'll be able to have a comfortable retirement and funding for projects that I want to sponsor.

## [Legacy](https://avisuj.github.io/categories/legacy)
I want to make the world a better place.  At Microsoft, I've had the opportunity to help organization leaders engage with their employees to drive improved engagement and affectiveness at accomplishing a variety of missions.  By helping employees connect with leaders, I've seen them make their organizations more responsive to changing environments and customer demands.  I've also had the opportunity to help health care organizations rethink how they engage with patients.  Through directed communication and intentional monitoring, I've seen organizations partner with patients to drive better health outcomes.

## What I write about
In this blog, I'm sharing my life experiences.  As such, I write about things that I'm interested in.  Many of my interests are captured above.  I don't expect that this blog will get a large following.  While there maybe some posts I choose to share, for the most part I'm treating this like a public diary.  This is my story.  This is my search for meaning.

## Timeline
A collection of important events in my life:
<STYLE>
.item {
padding-top:100px;
min-height:150px;
position:relative
}
.item:before,.last-item:after {
background:#fff;
border:8px solid #000;
border-radius:50%;
width:40px;
height:40px;
display:inline-block;
content:"";
margin-left:1rem;
position:relative;
z-index:1;
left:calc(2% - 36px)
}
.vertical-line {
width:8px;
background-color:#000;
position:absolute;
left:calc(2% - 5px);
top:0;
bottom:0
}
.item .card-panel {
margin:0;
margin:2rem 0 0 3rem
}
.item-date {
margin-top:-60px;
margin-left:4rem
}
.cv-title {
margin-bottom:0;
margin-left:calc(2% - 5px);
line-height:190%
}
.cv-title span {
padding:1rem
}
.last-item{
padding-top:80px;
height:70px;
position:relative
}
</STYLE>

<div class="container row">
    {% assign steps = site.steps | sort: 'date' | reverse %}
    {% for step in steps %}
    <div class="item">
        <i class="vertical-line"></i>
        <h2 class="item-date">{{ step.date | date: '%m/%Y' }}{% if step.enddate %} - {{ step.enddate | date: '%m/%Y' }}{% endif %}</h2>
        <div class="card-panel">
            <h3 class="card-title">
                {{ step.title }}
            </h3>
            <p>
                {{ step.content }}
            </p>
        </div>
    </div>
    {% endfor %}
    </div>