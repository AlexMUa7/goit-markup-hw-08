# goit-markup-hw-08

// utils styles
@import './utils/vars';
@import './utils/visually-hidden';
@import './utils/placeholders';
@import './utils/mixins';

// base styles
@import './base/common';
@import './base/reset';
@import './base/container';

// components styles
@import './components/logo';
@import './components/navigation';
@import './components/buttons';
@import './components/modal';
@import './components/rigistration-form';
@import './components/subscription-form';
@import './components/socials';

// layouts styles
@import './layouts/header';
@import './layouts/hero';
@import './layouts/features';
@import './layouts/works';
@import './layouts/team';
@import './layouts/clients';
@import './layouts/footer';
@import './layouts/portfolio';

.section-title {
color: #212121;
line-height: 1.14;
letter-spacing: 0.03em;
font-size: 14px;
text-transform: uppercase;
margin-top: 0%;
margin-bottom: 10px;
}

.title {
font-size: 36px;
line-height: 1.16;
text-align: center;
letter-spacing: 0.03em;
color: #212121;
}

.site-nav.team.list {
display: flex;
justify-content: space-between;
padding-top: 0px;
}

.site-nav .employees:not(:last-child) {
margin-right: 30px;
}
