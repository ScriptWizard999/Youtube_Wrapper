# Youtube_Wrapper

pip install my_youtube_package

usage


from my_youtube_package.data_api import get_video_details
from my_youtube_package.transcript_api import get_transcript

# Example usage
api_key = 'YOUR_API_KEY'
video_id = 'VIDEO_ID'
details = get_video_details(video_id, api_key)
transcript = get_transcript(video_id)
