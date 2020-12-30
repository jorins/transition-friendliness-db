# Transition-friendliness database
This repository documents how transition-friendly various services and products across the web are.

**This document is a work in progress.** Criteria have not been finalised, and a pipeline for easy contribution has yet to be developed. Anonymous contributions are not yet possible, though you can still write to me and I can add your testimonial anonymously.

**Table of contents:**

1. [Purpose](#1-purpose)
2. [Criteria](#2-criteria)
    1. [Basic criteria](#21-basic-criteria)
    2. [Additional criteria](#22-additional-criteria)
3. [Ratings](#3-ratings)
4. [Testimonials](#4-testimonials)
5. [Contributors](#5-contributors)
6. [License](#6-license)

## 1. Purpose
> Gender transitioning is the process of changing one's gender presentation and/or sex characteristics to accord with one's internal sense of gender identity – the idea of what it means to be a man or a woman, or to be non-binary or genderqueer.

\- [Wikipedia - Transitioning](https://en.wikipedia.org/wiki/Gender_transitioning)

A large part of transitioning is within social circles, which can include changing name, contact information, and many other details in many online contexts. For those who have a large online presence they wish to preserve, this entails a lot of labour. Lots of forms to fill out, support pages to dig through, tickets to write, and more. This database aims to define a standard for how an organisation or service can be supportive of its trans members in their transition, as well as keeping a record of how well organisations and services live up to this standard. Organisations that fail to meet the standard are strongly encouraged to submit an update through a pull request if they decide to change their procedure.

## 2. Criteria
Criteria are divided into basic criteria and additional criteria:

* **Basic criteria** define the minimum requirements to allow users to fully transition their user accounts.
* **Additional** criteria are extra criteria that, while not needed in order to perform a full account transition, make the process quicker, more accessible, and more discreet.

Score is comprised of 2 points. 1 point for basic criteria and 1 points for additional criteria. Each individual criteria contributes an equal fraction of one in its scope. No points are contributed for additional criteria if not all basic criteria are met. There are currently 6 basic criteria and 6 additional criteria, meaning that each basic criteria contributes one sixth of a point, and if all basic criteria are met, each additional criteria contributes one sixth of a point.

All criteria are put in one or more categories:

1. **Safety**: criteria that help the user stay safe and not suffer increased risk of harassment or doxxing.
2. **Accuracy**: criteria that allow the user to be accurately represented on a given platform.
3. **Equality**: criteria that reduce harm and discrimination against transgender individuals.
3. **User Experience**: criteria that allow the user to change necessary information without issues.

### 2.1. Basic criteria

| ID | Summary | Requirements | Rationale | Categories |
|----|---------|--------------|-----------|------------|
| B1 | **All personal information can be changed** | This includes name, gender, pronouns, and any other fields related to one's transition. This includes both privately and publicly shown information. Usernames, account names, character names, and similar are included. Even if they aren't guaranteed to be personal information, they may be used as such. | Publicly facing information that is incorrect may risk the user being misgendered. Incorrect private information might not pose a risk to the user, but many trans people find it painful to have to see their deadname and otherwise dated information. A mismatch in public information (for example, a display name being updated but a shown account name not being updated) can risk outing a trans user and their old identity can be tied to their new. This creates a risk of harassment and doxxing. | Safety, accuracy |
| B2 | **Changing information is free** | There should be no costs associated with any aspect of transitioning one's account. | Transitioning is an expensive process that can involve changing registered personal information with the state, paying for medication, therapists and psychologists, surgery, drastically changing wardrobes, and much more. To support trans people as a service provider, you should understand that transitioning is a hard process that is already very costly for trans people and it is unethical to ask more money of them to perform what is a necessary step in their own journey towards living as their true selves. | Equality |
| B3 | **Transition of an account is possible without data-loss** | No information stored by the user should be lost when changing, or be required to be manually transferred by the user. Creating a new account can qualify, but only if all service-related data is preserved and the old account can be fully removed. | Some trans people might opt to create entirely new accounts so as to make sure there is no connection between old and new, but others might find themselves needing account-tied information to be retained, such as game purchases on a game store or stored projects in a creative program. The latter group needs to be accounted for as not everyone can or wants to start with a clean slate. | Equality, User Experience |
| B4 | **Transition must be private and discreet** | A request to transition an account should not have to be filed in public as this puts the user at a risk of harassment. There should be no announcements made to others when information is changed. Historical information written by the user must be either removable or editable, even if doing so would be up to the user. | Transitioning is a very personal process and it is up to the person transitioning to choose whether to share information regarding their transition and to choose whom to share it with. | Safety |
| B5 | **Information should not be required to match state-issued ID** | The user has the final say on what information is stored about them. | A lot of, if not most, nation states make it hard or even entirely impossible to change registered gender marker and name. As a result, a lot of trans people live with incorrect names and gender markers on their ID and in state-administrated systems. No one but the person in question is an authority on who they are, not even a state. | Accuracy |
| B6 | **Non-binary individuals must be able to represent themselves** | Any gendered fields such as gender, honourifics, and pronouns, must be able to accurately represent non-binary users' preferences. Gender fields are not a requirement in most situations and having none fullfils this criteria but when they are present, the user should be able to input their own information in text inputs. If that's not possible, gender fields should have an "other" option, separate from "prefer not to tell" or blank input. Honourific fields should include the option "Mx." or an otherwise neutral choice. Pronoun fields should have an option for "they/them". | Non-binary people have always existed and will always exist. As such, they deserve to be able to show that where asked for their gender. Opt-out does not count as non-binary choices as it implies that the user either does not want to provide the information and not that they are non-binary. | Accuracy |

### 2.2. Additional criteria
| ID | Summary | Requirements | Rationale | Categories |
|----|---------|--------------|-----------|------------|
| A1 | **Single interface** | Transitioning should be possible from a single page or a set of directly related pages. You should not have to use two distinctly different interfaces to change different pieces of information. E-mail, phone calls, and such will be counted as their own interfaces. | Transitioning is a labourious process and users should not have to spend extensive time researching and navigating your service in order to transition. | User experience |
| A2 | **Self-service** | Transitioning should be possible to do without having to receive human support. | Self-servicing account management helps speed up the process greatly, reduces labour put in on both fronts, and can help reduce dysphoria and anxiety trans people face. | User experience |
| A3 | **Non-incrimating process** | The user should not have to present more personal information than what was given upon account creation in order to change stored information. | A service that trusts its user to provide accurate information upon registration should also trust them to update that information. Categorically treating trans people as less trustable is discriminatory. | Equality |
| A4 | **Non-binary individuals must be able to represent themselves _accurately_** | Services where there are gender options must allow non-binary users to accurately represent themselves through text fields or extensive choice lists. Multiple pronouns and neo-pronouns must be usable. | Generalising options that group all non-binary identities together fail to represent non-binary people with the same accuracy as those with binary identities. | Equality |
| A5 | **Reasonably fast execution** | Submitting a request to change account information and subsequently having it performed should not take more than a week. | A reasonably fast handling time helps users get peace of mind as they don't have to worry about whether their update is accepted once it is accepted. As updating account information can be a very taxing process that requires a person to open up a lot to strangers with regards to something very personal, quick handling can be a relief for them. | User experience |
| A6 | **Avoiding otherising of trans people** | Trans identities are only treated as separate from cis identities where strictly necessary. Cis should not be treated as a default or a 'normal'. | Trans people are the genders that they claim to be, just like cis people. Although there are differences between trans and cis people, these differences are virtually only relevant in medical contexts and studies. | Equality |

## 3. Ratings
**A note on hostility towards trans people:** Services and organisations that show hostility or malice towards trans people will be denoted as such in the ratings list and disqualify from receiving any rating in this document.

If you'd like to add a rating, first submit a testimonial!

| Service | Category | Testimonial IDs | Basic criteria met | Additional criteria met | Rating |
|---------|----------|-----------------|--------------------|-------------------------|--------|
|         |          |                 |                    |                         |        |
|         |          |                 |                    |                         |        |
|         |          |                 |                    |                         |        |

## 4. Testimonials

If you'd like to submit a testimonial, please send a pull request or submit an issue. There's not yet any quick way of doing this.

| Author | Service | Testimonial | Date of account transition |
|--------|---------|-------------|----------------------------|
|        |         |             |                            |

## 5. Contributors
* Jorin Seline

## 6. License
This document is presented with the CC-BY-SA license. Contributing to this document means accepting that your contribution is made under this license. It is your choice whether you want to be added to the contributors list. For the full license, see [LICENSE](./LICENSE)
