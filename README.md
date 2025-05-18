# Lộ trình công cộng GitHub

 :Tia sáng: Xem   [lộ trình sản phẩm công cộng GitHub chính thức](https://github.com/orgs/github/projects/4247)[^1]

Lộ trình sản phẩm của chúng tôi là nơi bạn có thể tìm hiểu về những tính năng chúng tôi đang làm việc, chúng đang ở giai đoạn nào, và khi nào chúng tôi mong đợi mang chúng đến với bạn. Có bất kỳ câu hỏi hoặc nhận xét nào về các mục trên lộ trình không? Chia sẻ phản hồi của bạn quA [Thảo luận phản hồi công khai](https://github.com/github/feedback/discussions) .   

Kho lưu trữ lộ trình là để truyền đạt lộ trình của GitHub. Các vấn đề hiện tại chỉ được đọc, và chúng tôi đang khóa các cuộc trò chuyện, khi chúng tôi bắt đầu. Giới hạn tương tác cũng được áp dụng để đảm bảo các vấn đề có nguồn gốc từ GitHub. Chúng tôi đang có kế hoạch lặp lại trên định dạng của chính lộ trình và chúng tôi thấy tiềm năng tham gia nhiều hơn vào các cuộc thảo luận về tương lai của các sản phẩm và tính năng GitHub. Nếu bạn có phản hồi về chính kho lưu trữ lộ trình này, chẳng hạn như cách trình  bày các vấn đề, hãy cho chúng tôi biết thông tin.H.  [Phản hồi chung trong GitHub Phản hồi công cộng thảo luận](https://github.com/orgs/community/discussions/new?category=general).


## Hướng dẫn về lộ trình

Every item on the roadmap is an issue, with a label that indicates each of the following:

- A **release phase** that describes the next expected phase of the roadmap item. See below for a guide to release phases. 

- A **feature area** that indicates the area of the product to which the item belongs. For a list of current product areas, see below.

- A **feature** that indicates the feature or product to which the item belongs. For a list of current features, see below. 

- One or more **product SKU** labels that indicate which product SKUs we expect the feature to be available in. For a list of current product SKUs, see below.

- One or more **deployment models** (cloud, server, and/or ae). Where not stated, features will generally come out Cloud first, and follow on Server and GHAE at or soon after GA.

- Once a feature is delivered, the **shipped** label will be applied to the roadmap issue and the issue will be closed with a comment linking to the relevant [Changelog](https://github.blog/changelog/) post.

## Release phases

Release phases indicate the stages that the product or feature goes through, from early testing to general availability.

- **preview:** *Publicly available in full or limited capacity*\
Features mostly complete and documented. Timeline and requirements for GA usually published. No SLAs or support provided.

- **ga:** *Generally available to all customers*\
Ready for production use with associated SLA and technical support obligations. Approximately 1-2 quarters from Preview.

Some of our features may still be in the exploratory stages, and have no timeframe available. These are included in the roadmap only for early feedback. These are marked as follows: 

- **in design:**\
Feature in discovery phase. We have decided to build this feature, but are still figuring out _how_.

- **exploring:**\
Feature under consideration. We are considering building this feature, and gathering feedback on it.

## Release phases - For GHES

Some features may be marked with a GHES 3.X label, which indicates that the feature will also become available for Github Enterprise Server customers. Below are the release version numbers and expected release quarters (_Note: these dates are subject to change_). 

**GHES release version dates**:
| **Version Number** | **Release Quarter** | **Release Notes** |
|-|-|-|
| 3.12 | Q1 2024 | [Release Notes](https://docs.github.com/en/enterprise-server@3.12/admin/release-notes#3.12.0)|
| 3.13 | Q2 2024 | [Release Notes](https://docs.github.com/en/enterprise-server@3.13/admin/release-notes#3.13.0)|
| 3.14 | Q3 2024 | [Release Notes](https://docs.github.com/en/enterprise-server@3.14/admin/release-notes) |
| 3.15 | Q4 2024 | -- |

## Roadmap stages

The roadmap is arranged on a project board to give a sense for how far out each item is on the horizon. Every product or feature is added to a particular project board column according to the quarter in which it is expected to ship next. Be sure to read the [disclaimer](#disclaimer) below since the roadmap is subject to change, especially further out on the timeline.  You'll also find an **Exploratory** column, which is used in conjunction with the **in design** and **exploring** release phase labels for when no timeframe is yet available.

GitHub Enterprise Server has major releases on a quarterly basis, and minor releases on a monthly basis. Once we know what version we are delivering a feature, we will update the issue to indicate that information.

## Feature Areas

The following is a list of our current product areas:

- **code:** Code experiences (Repositories, Pull Requests, Gists)
- **planning:** Planning and tracking tools (Issues, Projects)
- **code-to-cloud:** Code-to-cloud DevOps (Actions, Packages)
- **collaboration:** Collaboration features (Pages, Wikis, Discussions)
- **security & compliance:** Code security and compliance features
- **admin-server:** Administrative features specific to GitHub Enterprise Server
- **admin-cloud:** Administrative features specific to GitHub Cloud
- **communities:** Community and social features
- **ecosystem:** Ecosystem and API features
- **learning:** Education and learning features
- **insights:** Continuous learning and insights features
- **client-apps:** Client applications (Desktop, Mobile)
- **other:** Other features

## Feature

The following is a list of our current features and products, with distinct labels for filtering:

- **actions:** GitHub Actions
- **docs:** GitHub Docs
- **packages:** GitHub Packages
- **pages:** GitHub Pages

_More labels will be added in the future as needed._

## Product SKUs 

The following is a list of our current product SKUs. 

- **all:** Available to all users, including a free tier. Different SKUs may have different levels of functionality.
- **github team:** GitHub Team
- **github enterprise:** GitHub Enterprise (Cloud and Server)
- **github one:** GitHub One (Cloud and Server)
- **github ae:** GitHub AE (GHAE)
- **github advanced security:** GitHub Advanced Security (add-on to GHE)
- **github insights:** GitHub Insights (add-on to GHE)
- **github learning lab:** GitHub Learning Lab (add-on to GHE)

## Disclaimer 

Any statement in this repository that is not purely historical is considered a forward-looking statement. Forward-looking statements included in this repository are based on information available to GitHub as of the date they are made, and GitHub assumes no obligation to update any forward-looking statements. The forward-looking product roadmap does not represent a commitment, guarantee, obligation or promise to deliver any product or feature, or to deliver any product and feature by any particular date, and is intended to outline the general development plans. Customers should not rely on this roadmap to make any purchasing decision.
