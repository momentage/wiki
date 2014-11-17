## GET /v1/moments/featured

### Params
* page
* per

### Pagination
* ```next_page``` is returned if there is a next_page of moments (Last page returns no ```next_page```)

### Response
```js
{
    "moments": [
        {
            "id": "1",
            "description": "WBC behind the mesh!",
            "title": "",
            "tags": null,
            "privacy": "public",
            "url": "http://momentage.com/moments/1",
            "likes_count": 6,
            "comments_count": 2,
            "updated_at": 1407992618,
            "created_at": 1408434531,
            "featured_item_id": "56612",
            "moment_items": [
                {
                    "id": "56612",
                    "item_type": "photo",
                    "order": 0,
                    "audio_path": "",
                    "original_url": "http://d1zf6rn5lnsddj.cloudfront.net/moments/1/items/56612/chilepan_buer_140020140814-18174-1l9l2vq.jpg",
                    "preview_url": "http://d1zf6rn5lnsddj.cloudfront.net/moments/1/items/56612/low_chilepan_buer_140020140814-18174-1l9l2vq.jpg",
                    "large_url": "http://d1zf6rn5lnsddj.cloudfront.net/moments/1/items/56612/thumb_640_chilepan_buer_140020140814-18174-1l9l2vq.jpg",
                    "medium_url": "http://d1zf6rn5lnsddj.cloudfront.net/moments/1/items/56612/thumb_310_chilepan_buer_140020140814-18174-1l9l2vq.jpg",
                    "small_url": "http://d1zf6rn5lnsddj.cloudfront.net/moments/1/items/56612/thumb_200_chilepan_buer_140020140814-18174-1l9l2vq.jpg"
                },
                {
                    "id": "56603",
                    "item_type": "audiophoto",
                    "order": 0,
                    "audio_path": "",
                    "original_url": "53e9c613da0032303935aa99"
                },
                {
                    "id": "56602",
                    "item_type": "video",
                    "order": 0,
                    "audio_path": "",
                    "original_video_url": "http://d1zf6rn5lnsddj.cloudfront.net/moments/1/items/56602/56602.mp4",
                    "low_video_url": "http://d1zf6rn5lnsddj.cloudfront.net/moments/1/items/56602/low_56602.mp4",
                    "standard_video_url": "http://d1zf6rn5lnsddj.cloudfront.net/moments/1/items/56602/standard_56602.mp4"
                },
                {
                    "id": "56535",
                    "item_type": "audiophoto",
                    "order": 0,
                    "audio_path": "53e33d770e0706f13d37a3b0",
                    "original_url": "http://d1zf6rn5lnsddj.cloudfront.net/moments/1/items/56535/another_flower20140807-16506-wxvewd.jpg",
                    "preview_url": "http://d1zf6rn5lnsddj.cloudfront.net/moments/1/items/56535/low_another_flower20140807-16506-wxvewd.jpg",
                    "large_url": "http://d1zf6rn5lnsddj.cloudfront.net/moments/1/items/56535/thumb_640_another_flower20140807-16506-wxvewd.jpg",
                    "medium_url": "http://d1zf6rn5lnsddj.cloudfront.net/moments/1/items/56535/thumb_310_another_flower20140807-16506-wxvewd.jpg",
                    "small_url": "http://d1zf6rn5lnsddj.cloudfront.net/moments/1/items/56535/thumb_200_another_flower20140807-16506-wxvewd.jpg"
                },
                {
                    "id": "1",
                    "item_type": "photo",
                    "order": 4,
                    "audio_path": "",
                    "original_url": "http://assets.momentage.com/photos/5156206e9891e2daf9000035/a5405b0eb362d25075fd2fa9b0b099f3-original.jpg",
                    "large_url": "http://assets.momentage.com/photos/3/1/1-640x640.jpg",
                    "medium_url": "http://assets.momentage.com/photos/5156206e9891e2daf9000035/b7a5651a11c24bfe55d2156dee2452ef-thumb310x310.jpg",
                    "small_url": "http://assets.momentage.com/photos/3/1/1-200x200.jpg"
                }
            ],
            "user": {
                "id": "1",
                "name": "First User",
                "username": "default_user1",
                "avatar": "https://s3.amazonaws.com/momentage-files/assets/email/default_avatar2.png",
                "background": "https://momentage-assets.s3.amazonaws.com/cover/CoverPhotoPlaceHolder.jpg",
                "one_liner": "user@example.com",
                "moments_count": 6,
                "followers_count": 0,
                "following_count": 2,
                "followed_by_me": false
            },
            "liked_by_me": true
        }
    ]
}
```