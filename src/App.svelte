<script>
	import FeedbackForm from "./components/FeedbackForm.svelte";
    import FeedbackItem from "./components/FeedbackItem.svelte";
    import FeedbackList from "./components/FeedbackList.svelte";
	import FeedbackStats from "./components/FeedbackStats.svelte";
    
	// let feedback = [
	// 	{
	// 		id:1,
	// 		rating:10,
	// 		text:'Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequuntur vel vitae commodi alias voluptatemest voluptatum ipsa quae.',
	// 	},
	// 	{
	// 		id:2,
	// 		rating:9,
	// 		text:'Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequuntur vel vitae commodi alias voluptatemest voluptatum ipsa quae.'
	// 	},
	// 	{
	// 		id:3,
	// 		rating:8,
	// 		text:'Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequuntur vel vitae commodi alias voluptatemest voluptatum ipsa quae.',
	// 	},
	// ]

	

	// const addFeedback = (e) => {
	// 	const newFeedback = e.detail
	// 	feedback = [newFeedback,...feedback]
	// }

	// const deleteFeedback = (e) =>{
	// 	const itemId = e.detail
	// 	feedback = feedback.filter((item) => item.id!=itemId)
	// }
</script>

<main class="container">
	<FeedbackForm />
	<FeedbackStats />
	<FeedbackList  />	
</main>

