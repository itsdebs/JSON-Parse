package parseJSONToTree;

import org.json.JSONObject;

public interface IJSONParse {

	JSONObject changeToTree(JSONObject obj); // takes the json object with name "model" as parent
	JSONObject changeToTree(JSONObject obj, JSONObject init);// specify parent object
	JSONObject changeToTree(JSONObject obj, String init);	// specify parent object id as string
	
	public void initialize(JSONObject obj);
	String findIdByName(String name); // find the name of object with name as id
}
