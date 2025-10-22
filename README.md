# Amazon Reviews 2023 Dataset

## Dataset Overview

The dataset includes three main components:

1. **User Reviews** – Ratings, text, helpfulness votes, and more.  
2. **Item Metadata** – Product descriptions, prices, and images.  
3. **Links** – Graphs connecting users and items (e.g., “bought together” relationships).

**Source:** [Hugging Face – McAuley-Lab/Amazon-Reviews-2023](https://huggingface.co/datasets/McAuley-Lab/Amazon-Reviews-2023)

---

## Dataset Fields

| Field | Type | Description |
|-------|------|-------------|
| `rating` | `float` | Product rating (from 1.0 to 5.0). |
| `title` | `str` | Title of the user review. |
| `text` | `str` | Text body of the user review. |
| `images` | `list` | List of images posted by users after receiving the product. Each image has multiple sizes: `small_image_url`, `medium_image_url`, `large_image_url`. |
| `asin` | `str` | Product ID. |
| `parent_asin` | `str` | Parent product ID (e.g., same product with different colors, sizes, or styles). Use this field to find product metadata. |
| `user_id` | `str` | Reviewer ID. |
| `timestamp` | `int` | Time of the review (Unix time). |
| `verified_purchase` | `bool` | Indicates whether the reviewer purchased the product. |
| `helpful_vote` | `int` | Number of helpful votes for the review. |

---
